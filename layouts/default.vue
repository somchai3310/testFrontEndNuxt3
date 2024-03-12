<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p-1 flex justiy-between">

        <NuxtLink to="/" class="">
          <img src="~/assets/images/logo/logo.png" alt="menu-icon" class="w-20" />
        </NuxtLink>
        <ul class="flex gap-4">
          <li><inline-svg src="~/assets/icons/home.svg" width="20" height="20" aria-label="see-all-icon" class="ml-1" />หน้าหลัก</li>
          <li>faq</li>
          <li>บทความ</li>
          <li>ติดต่อเรา</li>
        </ul>
      </nav>
    </header>

    <!-- content -->
    <div class="container mx-auto p-4">
      <slot />
    </div>

    <footer class="container mx-auto p-4 flex justify-between border-t-2">
      <ul class="flex gap-4">
        <li>Home</li>
        <li>About</li>
        <li>Products</li>
      </ul>
    </footer>
  </div>
</template>

<script setup>

</script>

<style scoped></style>

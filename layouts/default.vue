<template>
  <div>
    <header class="shadow-sm bg-white flex justify-center">
      <div class="authLoggedIn container mx-auto p-1 flex justiy-between">
        <div class="left-header flex flex-auto">
          <div class="logo">
            <NuxtLink to="/" class="">
              <img src="~/assets/images/logo/logo.png" alt="menu-icon" class="w-20" />
            </NuxtLink>
          </div>
          <div class="page flex">
            <div class="flex h-11">
              <nuxt-icon name="home" color="black"></nuxt-icon>
              <div>หน้าหลัก</div>
            </div>
            <div class="flex h-11">
              <nuxt-icon name="faq"></nuxt-icon>
              <div>faq</div>
            </div>
            <div class="flex h-11">
              <nuxt-icon name="blog"></nuxt-icon>
              <div>บทความ</div>
            </div>
            <div class="flex h-11">
              <nuxt-icon name="contact"></nuxt-icon>
              <div>ติดต่อเรา</div>
            </div>
          </div>
        </div>
        <div class="right-header flex justify-end">
          <div class="register-login">
            <button class="btn btn-primary w-18">Register</button>
            <button class="btn btn-secondary w-18 border-none">Login</button>
          </div>
          <div class="lang flex bg-gray-500">
            <div class="langText">
              <p>TH</p>
            </div>
            <div class="flag">
              <img height="14" src="~/assets/images/flag/th.png" alt="flag">
            </div>
          </div>
        </div>
      </div>
      <!-- <nav class="container mx-auto p-1 flex justiy-between">


        <ul class="flex gap-4">
          <li><inline-svg src="~/assets/icons/home.svg" width="20" height="20" aria-label="see-all-icon"
              class="ml-1" />หน้าหลัก</li>
          <li>faq</li>
          <li>บทความ</li>
          <li>ติดต่อเรา</li>
        </ul>
      </nav> -->
    </header>

    <!-- content -->
    <div class="container mx-auto px-[70px]">
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

<style scoped>
.nuxt-icon svg{
  color: black;
}
</style>

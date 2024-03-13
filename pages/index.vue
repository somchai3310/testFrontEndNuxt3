<template>
  <div>
    <!-- Banner side -->
    <div class="bannerSide mx-38">
      <div class="carousel w-full">
        <div id="item1" class="carousel-item w-full">
          <img src="~/assets/images/slide/slide1.png" class="w-full" />
        </div>
        <div id="item2" class="carousel-item w-full">
          <img src="~/assets/images/slide/slide2.png" class="w-full" />
        </div>
        <div id="item3" class="carousel-item w-full">
          <img src="~/assets/images/slide/slide3.png" class="w-full" />
        </div>
        <div id="item4" class="carousel-item w-full">
          <img src="~/assets/images/slide/slide4.png" class="w-full" />
        </div>
      </div>
      <div class="flex justify-center w-full py-2 gap-2">
        <a href="#item1" class="btn btn-xs">1</a>
        <a href="#item2" class="btn btn-xs">2</a>
        <a href="#item3" class="btn btn-xs">3</a>
        <a href="#item4" class="btn btn-xs">4</a>
      </div>

    </div>
    <!-- notebook / gaming -->
    <div class="notebookGaming">
      <div class="top">
        <!-- <div role="tablist" class="tabs tabs-bordered"> -->
        <div role="tablist" class="tabs tabs-bordered">
          <input type="radio" name="my_tabs_1" role="tab" class="tab" aria-label="Notebook" checked />
          <div role="tabpanel" class="tab-content py-10">
            <div class="flex flex-wrap gap-2">
              <div class="bg-red-500 w-[200px] h-[200px]"></div>
              <div class="bg-red-500 w-[200px] h-[200px]"></div>
              <div class="bg-red-500 w-[200px] h-[200px]"></div>
              <div class="bg-red-500 w-[200px] h-[200px]"></div>
              <div class="bg-red-500 w-[200px] h-[200px]"></div>
              <div class="bg-red-500 w-[200px] h-[200px]"></div>
              <div class="bg-red-500 w-[200px] h-[200px]"></div>
              <div class="bg-red-500 w-[200px] h-[200px]"></div>
              <div class="bg-red-500 w-[200px] h-[200px]"></div>
            </div>
          </div>

          <input type="radio" name="my_tabs_1" role="tab" class="tab" aria-label="GAMING GEAR" />
          <div role="tabpanel" class="tab-content py-10">
            <div class="flex flex-wrap gap-2">
              <div class="bg-blue-500 w-[200px] h-[200px]"></div>
              <div class="bg-blue-500 w-[200px] h-[200px]"></div>
              <div class="bg-blue-500 w-[200px] h-[200px]"></div>
              <div class="bg-blue-500 w-[200px] h-[200px]"></div>
              <div class="bg-blue-500 w-[200px] h-[200px]"></div>
              <div class="bg-blue-500 w-[200px] h-[200px]"></div>
              <div class="bg-blue-500 w-[200px] h-[200px]"></div>
              <div class="bg-blue-500 w-[200px] h-[200px]"></div>
              <div class="bg-blue-500 w-[200px] h-[200px]"></div>
            </div>
          </div>
          <button class="btn btn-primary flex justify-end">ทั้งหมด</button>
        </div>
      </div>
    </div>
    <!-- IT -->
    <div class="it">
      <div class="top">
        <div class="text">อุปกรณ์ไอที</div>
        <div class="right">
          <button class="btn btn-primary flex justify-end">ทั้งหมด</button>
          <!-- ปุ่ม ซ้าย ขวา -->
        </div>
      </div>
      <div class="it">
        <div class="one-card">
          <img class="w-[239px] h-[239] rounded" src="~/assets/images/it/custom-radio-img-1.png" alt="">
          <p>treasure heroes</p>
        </div>
      </div>
    </div>
    <!-- side -->
    <div class="side">
      <div class="carousel carousel-center  p-4 space-x-4 bg-neutral rounded-box">
        <div class="carousel-item">
          <img src="https://daisyui.com/images/stock/photo-1559703248-dcaaec9fab78.jpg" class="rounded-box" />
        </div>
        <div class="carousel-item">
          <img src="https://daisyui.com/images/stock/photo-1565098772267-60af42b81ef2.jpg" class="rounded-box" />
        </div>
        <div class="carousel-item">
          <img src="https://daisyui.com/images/stock/photo-1572635148818-ef6fd45eb394.jpg" class="rounded-box" />
        </div>
        <div class="carousel-item">
          <img src="https://daisyui.com/images/stock/photo-1494253109108-2e30c049369b.jpg" class="rounded-box" />
        </div>
        <div class="carousel-item">
          <img src="https://daisyui.com/images/stock/photo-1550258987-190a2d41a8ba.jpg" class="rounded-box" />
        </div>
        <div class="carousel-item">
          <img src="https://daisyui.com/images/stock/photo-1559181567-c3190ca9959b.jpg" class="rounded-box" />
        </div>
        <div class="carousel-item">
          <img src="https://daisyui.com/images/stock/photo-1601004890684-d8cbf643f5f2.jpg" class="rounded-box" />
        </div>
      </div>
      <div class="flex justify-center w-full py-2 gap-2">
        <a href="#item1" class="btn btn-xs">1</a>
        <a href="#item2" class="btn btn-xs">2</a>
        <a href="#item3" class="btn btn-xs">3</a>
        <a href="#item4" class="btn btn-xs">4</a>
      </div>
    </div>
    <!-- อุปกรณ์เสริม -->
    <div class="accessories">
      <div class="top">
        <div class="left">
          icons
          <p>อุปกรณ์เสริม</p>
        </div>
        <div class="right">
          <button class="btn btn-primary flex justify-end">ทั้งหมด</button>
        </div>
      </div>
    </div>
    <!-- provider Google -->
    <div class="provider">
      <h1>provider</h1>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped></style>

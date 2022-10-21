<template>
  <div>
    <VueSlickCarousel v-bind="settings">
      <div class="relative flex w-full">
        <img class="flex object-cover object-center w-full lg:w-3/4" src="https://i0.wp.com/noithatzip.com/uploads/auto/slide/olive.jpg?resize=800%2C600&ssl=1" alt="">
        <div class="absolute w-full lg:right-0 bottom-0 lg:h-full lg:w-1/4 lg:px-5 lg:pt-[200px] bg-black text-center py-5">
          <h2 class="uppercase leading-5 text-xl text-white lg:text-2xl lg:leading-9">Bàn thông minh Olive</h2>
          <p class="text-white pt-2">Phù hợp cho mọi lứa tuổi - thay đổi độ cao tự động 70-110cm-bàn phấn-giá vẽ-bàn laptop...</p>
          <button class="mx-2 my-2 bg-white transition duration-150 ease-in-out focus:outline-none rounded text-gray-800 border border-gray-300 px-6 py-2 uppercase text-sm">Mua ngay</button>
        </div>
      </div>

      <div class="relative flex w-full">
        <img class="flex object-cover object-center w-full lg:w-3/4" src="https://i0.wp.com/noithatzip.com/uploads/auto/slide/iris.jpg?resize=800%2C600&ssl=1" alt="">
        <div class="absolute w-full lg:right-5 bottom-0 lg:h-full lg:w-1/4 lg:px-5 lg:pt-[200px] bg-black text-center py-5">
          <h2 class="uppercase leading-5 text-xl text-white lg:text-2xl lg:leading-9">GIƯỜNG TẦNG IRIS NEW</h2>
          <p class="text-white pt-2">Giường tầng 7 tính năng - sự lựa chọn số 1 cho thiết kế phòng ngủ thông minh của 2 con</p>
          <button class="mx-2 my-2 bg-white transition duration-150 ease-in-out focus:outline-none rounded text-gray-800 border border-gray-300 px-6 py-2 uppercase text-sm">Mua ngay</button>
        </div>
      </div>
      <div class="relative flex w-full">
        <img class="flex object-cover object-center w-full lg:w-3/4" src="https://i0.wp.com/noithatzip.com/uploads/auto/slide/2.jpg?resize=800%2C600&ssl=1" alt="">
        <div class="absolute w-full lg:right-5 bottom-0 lg:h-full lg:w-1/4 lg:px-5 lg:pt-[200px] bg-black text-center py-5">
          <h2 class="uppercase leading-5 text-xl text-white lg:text-2xl lg:leading-9">GIƯỜNG SOFA IVY</h2>
          <p class="text-white pt-2">Giường không cần bắt vít cố định - Không có khung hộp bao che - Nâng hạ giường chỉ với 1 thao tác</p>
          <button class="mx-2 my-2 bg-white transition duration-150 ease-in-out focus:outline-none rounded text-gray-800 border border-gray-300 px-6 py-2 uppercase text-sm">Mua ngay</button>
        </div>
      </div>
      <div class="relative flex w-full">
        <img class="flex object-cover object-center w-full lg:w-3/4" src="https://i0.wp.com/noithatzip.com/uploads/auto/slide/3.jpg?resize=800%2C600&ssl=1" alt="">
        <div class="absolute w-full lg:right-5 bottom-0 lg:h-full lg:w-1/4 lg:px-5 lg:pt-[200px] bg-black text-center py-5">
          <h2 class="uppercase leading-5 text-xl text-white lg:text-2xl lg:leading-9">GIƯỜNG BÀN HỌC TULIP</h2>
          <p class="text-white pt-2">Giường không cần bắt vít cố định - Không có khung hộp bao che - chất liệu cao cấp, dễ vệ sinh</p>
          <button class="mx-2 my-2 bg-white transition duration-150 ease-in-out focus:outline-none rounded text-gray-800 border border-gray-300 px-6 py-2 uppercase text-sm">Mua ngay</button>
        </div>
      </div>
      <div class="relative flex w-full">
        <img class="flex object-cover object-center w-full lg:w-3/4" src="https://i0.wp.com/noithatzip.com/uploads/auto/slide/3.jpg?resize=800%2C600&ssl=1" alt="">
        <div class="absolute w-full lg:right-5 bottom-0 lg:h-full lg:w-1/4 lg:px-5 lg:pt-[200px] bg-black text-center py-5">
          <h2 class="uppercase leading-5 text-xl text-white lg:text-2xl lg:leading-9">GIƯỜNG BÀN HỌC TULIP</h2>
          <p class="text-white pt-2">Giường không cần bắt vít cố định - Không có khung hộp bao che - chất liệu cao cấp, dễ vệ sinh</p>
          <button class="mx-2 my-2 bg-white transition duration-150 ease-in-out focus:outline-none rounded text-gray-800 border border-gray-300 px-6 py-2 uppercase text-sm">Mua ngay</button>
        </div>
      </div>
    </VueSlickCarousel>
  </div>
</template>
 
<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
 
  export default {
    name: 'MyComponent',
    components: { VueSlickCarousel },
    data(){
      return{
        settings:{
          "dots": true,
          "infinite": true,
          "slidesToShow": 1,
          "slidesToScroll": 1,
          "autoplay": true,
          "autoplaySpeed": 2000,
          "pauseOnDotsHover": true,
          "pauseOnFocus": true,
          "pauseOnHover": true,
          "arrows":false
        }
      }
    }
  }
</script> 
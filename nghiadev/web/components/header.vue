<script setup>
import Search from './icon/Search.vue'
</script>

<template>
  <div class="fixed w-full z-[100] pointer-events-none">
   
    <!-- header top -->
  <div
    class="fixed top-0 left-0 w-full px-[5%] py-[10px] flex justify-between items-center shadow-md border-b border-[#070001]"
  >
    <!-- header-left -->
    <div class="flex items-center left-6">
      <div class="w-9 h-9 rounded-full m-[15px] pointer-events-auto">
        <img
          src="../img/images.png"
          alt="avata"
          class="w-full h-auto rounded-full transition-all duration-500 ease-in-out hover:scale-110 hover:-translate-y-[5px] hover:shadow-[0_0_25px_#013f6e]"
        />
      </div>
      <h3 class="ml-3 text-xl">Học tập để đi làm</h3>
    </div>

    <!-- header-between -->
    <Search />

    <!-- header-right -->
    <div class="flex right-6">
      <button
        class="h-[50px] w-[70px] font-bold bg-transparent transition-all duration-500 ease-in-out pointer-events-auto text-sm hover:scale-110 hover:-translate-y-[5px] hover:border-b hover:border-[#013f6e] cursor-pointer"
      >
        Đăng kí
      </button>
      <button
        class="h-[50px] w-[80px] font-bold rounded-[18px] bg-[#1797f9] text-white ml-[15px] transition-all duration-500 ease-in-out pointer-events-auto flex items-center justify-center text-sm hover:scale-110 hover:-translate-y-[5px] hover:border-b hover:border-[#013f6e] cursor-pointer"
      >
        Đăng nhập
      </button>
    </div>
  </div>
  <!-- header left -->
   <div class="h-[70vh] w-[100px] flex flex-col justify-between items-center mt-[100px] fixed left-0 top-0 pointer-events-none">
     <div>
       <div class="w-[60px] h-[50px] m-[35px] flex flex-col justify-center items-center transition-all ease-in-out duration-500 pointer-events-auto
        hover:scale-110 hover:-translate-y-[5px]
           hover:border hover:border-[#312b2b]
           hover:shadow-[0_0_25px_#494242]
           hover:bg-[#686666] hover:text-white
           hover:rounded-[25px]">
        <button><ion-icon name="home-outline"></ion-icon></button>
        <h6 class="text-xs whitespace-nowrap">Trang chủ</h6>
      </div>
      <!--  -->
      
      <div class="w-[60px] h-[50px] m-[35px] flex flex-col justify-center items-center transition-all ease-in-out duration-500 pointer-events-auto
       hover:scale-110 hover:-translate-y-[5px]
           hover:border hover:border-[#312b2b]
           hover:shadow-[0_0_25px_#494242]
           hover:bg-[#686666] hover:text-white
           hover:rounded-[25px]">
        <button><ion-icon name="receipt-outline"></ion-icon></button>
        <h6 class="text-xs">Lộ trình</h6>
      </div>

      <!--  -->
      <div class="w-[60px] h-[50px] m-[35px] flex flex-col justify-center items-center transition-all ease-in-out duration-500 pointer-events-auto
       hover:scale-110 hover:-translate-y-[5px]
           hover:border hover:border-[#312b2b]
           hover:shadow-[0_0_25px_#494242]
           hover:bg-[#686666] hover:text-white
           hover:rounded-[25px]">
        <button><ion-icon name="chatbox-ellipses-outline"></ion-icon></button>
        <h6 class="text-xs">Bài Viết</h6>
      </div>
     </div>
     <!--  -->
     <div class="w-[60px] h-[50px] m-[35px] flex justify-center items-center transition-all ease-in-out duration-500 pointer-events-auto
     hover:scale-110 hover:-translate-y-[5px]
           hover:border hover:border-[#312b2b]
           hover:shadow-[0_0_25px_#494242]
           hover:bg-[#686666] hover:text-white
           hover:rounded-[25px]">
        <button><ion-icon name="volume-high-outline"></ion-icon></button>

     </div>
    </div>

  </div>
</template>

<template>
  <div class="flex h-screen container mx-auto relative">
    <div class="w-20  xl:w-1/6 pt-5 flex flex-col border-r border-gray-100 xl:ml-10">
      <div class="flex flex-col items-center xl:items-start">
        <!--logo -->
        <div class="flex items-center xl:items-start mb-3">
          <i class="fas fa-seedling text-3xl text-primary"></i>
          <p class="text-3xl hidden xl:inline-block font-medium hidden text-primary">study</p>
       </div>
       <div class="flex flex-col items-start">
        <a class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full cursor-pointer">
        <i class="fas fa-calendar-alt text-2xl"></i>
        <span class="xl:inline-block hidden text-lg ml-3">달력보기</span>
        </a>
      </div>
      <div class="flex flex-col items-start">
        <a class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full cursor-pointer">
        <i class="fas fa-check-circle text-2xl"></i>
        <span class="xl:inline-block hidden text-lg ml-3">오늘의일정</span>
        </a>
      </div>
      <div class="flex flex-col items-start">
        <a class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full cursor-pointer">
        <i class="fas fa-signal text-2xl"></i>
        <span class="xl:inline-block hidden text-lg ml-3">공부통계</span>
        </a>
      </div>
      <div class="flex flex-col items-start">
       <a class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full cursor-pointer">
       <i class="far fa-thumbs-up text-2xl"></i>
       <span class="xl:inline-block hidden text-lg ml-3">챌린지</span>
       </a>
      </div>
      <div class="flex flex-col items-start">
       <a class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full cursor-pointer">
       <i class="far fa-user text-2xl"></i>
       <span class="xl:inline-block hidden text-lg ml-3">프로필</span>
       </a>
      </div>
      </div>
      <div class="w-full mt-7 flex justify-center xl:pr-3">
        <button class="bg-primary text-white w-full h-12 rounded-full hover:bg-green-400  hover:opacity-80">
          <span class="hidden xl:block">오늘의 일정 추가</span>
          <i class="far fa-calendar-plus block xl:hidden"></i>
        </button>
      </div>
    </div>
    <div class="flex-1 flex h-screen">
      <div class="mt-10 ml-3 flex">
        <img src="https://picsum.photos/250/250" class="w-10 h-10 rounded-full"/>
        <span class="ml-3 mt-2 text-base text-gray-500 font-bold">혜원님, 오늘의 일정을 알려주세요.</span>
      </div>
    </div>
  </div>
</template>

<script>


export default {
  name: 'App',
  components: {
   
  }
}
</script>

<style>

</style>

<template>
  <div class="flex h-screen container mx-auto relative">
    <div class="w-20  xl:w-1/4 pt-5 flex flex-col justify-between border-r border-gray-100 xl:ml-10">
      <div class="flex flex-col items-center xl:items-start">
        <div class="flex items-center xl:items-start mb-3">
          <i class="fas fa-seedling text-3xl text-primary"></i>
          <p class="text-3xl hidden xl:inline-block font-medium hidden text-primary">study</p>
       </div>
       <div class="flex flex-col items-start">
       <a class="hover:text-primary hover:bg-blue-50 px-4 py-2 rounded-full cursor-pointer">
       <i class="fas fa-calendar-alt text-2xl"></i>
       <span class="xl:inline-block hidden text-xl ml-3">달력보기</span>
       </a>
      </div>
      </div>
    </div>
    <div class="flex-1 flex h-screen"></div>
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

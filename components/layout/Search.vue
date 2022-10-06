<template>
  <div class="flex justify-center h-[3.75rem] rounded-2xl">
    <div class=" flex justify-between h-11 w-[68.375rem] my-2">
        <div class="flex ml-2.5 w-[23.635rem] h-full">
          <img src="~/assets/icon/search.png" class="w-4 h-4 my-auto">
          <input class="bg-transparent ml-2 grow placeholder-white placeholder-opacity-70 focus:outline-0" placeholder="Search destinations, hotels">
        </div>
        <div class="flex justify-between">
          <div class="flex w-[9.8175rem]">
            <img src="~/assets/icon/checkin.png" class="w-4 h-4 my-auto">
            <span class="text-white/70 ml-2 my-auto">Check in</span>
          </div>
          <div class="flex w-[9.8175rem]">
            <img src="~/assets/icon/checkout.png" class="w-4 h-4 my-auto">
            <span class="text-white/70 ml-2 my-auto">Check out</span>
          </div>
          <div class="flex w-[9.8175rem]">
            <img src="~/assets/icon/person.png" class="w-4 h-4 my-auto">
            <span class="text-white/70 ml-2 my-auto"> 1 room, 2 adults</span>
          </div>
          <button class="text-[#2659C3] bg-white h-[2.625rem] w-[9.1875rem] rounded-[32px] font-bold" >Search</button>
        </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Search"
}
</script>

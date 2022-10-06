<template>
<!--  tổng-->
 <div class="h-[544px] mt-[140px] relative">
   <img src="~/assets/background/mountain.png" class="w-full h-full absolute -z-10">

<!--   Nội dung-->
   <div class="flex">

     <!--   ảnh điện thoại-->
     <img src="~/assets/phone/iPhone13pro.png" class="mt-[76px] ml-[135px]">
     <!--   hết ảnh điện thoại-->

<!--     Nội dung chia theo flex column-->
     <div class="flex flex-col max-w-[772px] mt-[76px] ml-[36px]">
<!--       Giới thiệu-->
       <div>
         <p class="text-5xl text-white font-bold">
           Your all-in-one travel app.
         </p>
         <p class="text-white text-2xl leading-7 mt-6">
           Book flights, hotels, trains & rental cars anywhere in the world in just seconds. Get real-time flight updates, travel info, exclusive deals, and 30% more Trip Coins only on the app!
         </p>
       </div>
<!--       Hết giới thiệu-->
<!--       loại liên hệ chia theo flex row-->
       <div class="flex justify-between mt-10 ">
<!--         row 1-->
         <div class="flex flex-col">
           <div class="flex h-[39px]">
             <span class="text-white text-[20px] px-4 py-2 leading-[23px] bg-white/40 backdrop-blur-md w-[90px] rounded-2xl">
             Mobile
             </span>
             <span class="text-white text-[20px] px-4 py-2 ml-4 leading-[23px] w-[90px]">
             Email
             </span>
           </div>
           <p class="text-white text-[14px] mt-4">Enter your phone number to receive a text with a link to download the app.</p>
           <div class="flex justify-center h-[58px] rounded-2xl mx-auto mt-4 bg-white/40 backdrop-blur-md max-w-[462px]	">
             <div class=" flex justify-between h-11 w-[462px] my-2">
               <input class="bg-transparent ml-6 grow placeholder-white placeholder-opacity-70 focus:outline-0" placeholder="+91  Mobile number">
               <button class="text-[#2659C3] bg-white mr-4 h-[42px] w-[188px] rounded-[32px] font-bold" >Search</button>
             </div>
           </div>
         </div>
<!--         hết row 1 -->
<!--         row2-->
        <div>
          <img src="~/assets/store/ggplay.png" class="pl-[50px] border-l border-white/20">
          <p class="text-white -ml-[7px] py-2">or</p>
          <img src="~/assets/store/appstore.png" class="pl-[50px]  border-l border-white/20">
        </div>
<!--         hết row2-->
       </div>
<!--       hết loại liên hệ-->
     </div>
<!--     Hết nội dung chia theo flex column-->
   </div>
<!--   hết nội dung-->
 </div>
<!--  hết tổng-->
</template>

<script>
export default {
  name: "Contact"
}
</script>

<style scoped>

</style>

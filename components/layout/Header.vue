<template>
  <div class="relative">
    <div>
      <img src="~/assets/background/image.jpg" class="absolute w-screen -z-10 h-[52.625rem]">
      <div class="gradient"></div>
    </div>
    <div class="flex justify-between mr-12">
      <div>
        <img src="~/assets/logo/trxvl.png" class="my-6 ml-12 p-0.5">
      </div>
      <div class="flex space-x-6">
        <MenuHeaderItem title="Home"></MenuHeaderItem>
        <MenuHeaderItem title="Stays"></MenuHeaderItem>
        <MenuHeaderItem title="Flights"></MenuHeaderItem>
        <MenuHeaderItem title="Packages"></MenuHeaderItem>
        <MenuHeaderItem title="Sign up" isBold></MenuHeaderItem>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header"
}
</script>
<style>
  .gradient {
    background: linear-gradient(180deg, rgba(255, 255, 255, 0) 0%, #FFFFFF 89.58%);
    position:absolute;
    display:block;
    z-index: 10;
    height:105px;
    width: 100%;
    top: 739px;
  }
</style>






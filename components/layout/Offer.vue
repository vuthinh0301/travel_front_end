<template>
  <div class="mt-20">
    <p class="text-[32px] font-bold  ml-[12.25rem]">Offers</p>
    <div class="slide flex gap-x-[24px] justify-start overflow-x-auto mt-8 h-[290px]">
      <OfferItem></OfferItem>
      <OfferItem></OfferItem>
      <OfferItem></OfferItem>
      <OfferItem></OfferItem>
      <OfferItem></OfferItem>
    </div>
  </div>
</template>

<script>

export default {
  name: "Offer"
}
</script>

<style scoped>
.slide::-webkit-scrollbar {
  display: none;
  direction: ltr;
}
</style>

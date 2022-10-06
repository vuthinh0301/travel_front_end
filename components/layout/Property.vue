<template>
    <div>
      <p class="mt-20 text-[32px] font-bold ml-[12.25rem]">Browse by property type</p>
      <div class="slide flex gap-x-6 justify-start mt-10 h-[12.5rem] overflow-x-auto">
        <SlideItem destination="property/hotel.png" info="Hotels"></SlideItem>
        <SlideItem destination="property/apartment.png" info="Apartments"></SlideItem>
        <SlideItem destination="property/resort.png" info="Resorts"></SlideItem>
        <SlideItem destination="property/apartment.png" info="Apartments"></SlideItem>
        <SlideItem destination="property/apartment.png" info="Apartments"></SlideItem>

      </div>
    </div>
</template>

<script>
export default {
  name: "Property"
}
</script>
<style scoped>
.slide::-webkit-scrollbar {
  display: none;
  direction: ltr;
}
</style>


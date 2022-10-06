<template>
  <div class="slide flex gap-x-6 justify-start mt-10 h-[12.5rem] overflow-x-auto">
    <SlideItem destination="destination/bali.png" info="Bali, Indonesia"></SlideItem>
    <SlideItem destination="destination/ireland.png" info="Kerry, Ireland"></SlideItem>
    <SlideItem destination="destination/sydney.png" info="Sydney, Australia"></SlideItem>
    <SlideItem destination="destination/ireland.png" info="Kerry, Ireland"></SlideItem>
    <SlideItem destination="destination/ireland.png" info="Kerry, Ireland"></SlideItem>
    <SlideItem destination="destination/ireland.png" info="Kerry, Ireland"></SlideItem>
    <SlideItem destination="destination/ireland.png" info="Kerry, Ireland"></SlideItem>
    <SlideItem destination="destination/ireland.png" info="Kerry, Ireland"></SlideItem>
    <SlideItem destination="destination/ireland.png" info="Kerry, Ireland"></SlideItem>
    <SlideItem destination="destination/ireland.png" info="Kerry, Ireland"></SlideItem>
  </div>
</template>

<script>
export default {
  name: "SlideDestination"
}
</script>

<style scoped>
    .slide::-webkit-scrollbar {
      display: none;
      direction: ltr;
    }
</style>

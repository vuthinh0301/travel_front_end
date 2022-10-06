<template>
  <div>
    <Header />
    <p class="font-bold text-7xl text-white max-w-[47.5rem] ml-[12.25rem] leading-[5.125rem]">The whole world awaits.</p>
    <Search class="mx-auto mt-10 bg-white/40 backdrop-blur-md max-w-[70.375rem]	"></Search>
    <p class="mt-10 font-bold text-[32px] text-white ml-[12.25rem]">Top categories</p>
    <div class="flex justify-between gap-10 mt-8 ml-[12.25rem] max-w-[70.375rem]">
      <PlaceListItem file_name="beach.png" title="Beaches"></PlaceListItem>
      <PlaceListItem file_name="desert.png" title="Deserts"></PlaceListItem>
      <PlaceListItem file_name="mountain.png" title="Mountains"></PlaceListItem>
      <PlaceListItem file_name="cities.png" title="Iconic Cities"></PlaceListItem>
      <PlaceListItem file_name="house.png" title="Houseboats"></PlaceListItem>
      <PlaceListItem file_name="country.png" title="Countryside" isBold></PlaceListItem>
      <PlaceListItem file_name="camping.png" title="Camping"></PlaceListItem>
      <PlaceListItem file_name="castles.png" title="Castles"></PlaceListItem>
      <PlaceListItem file_name="skiing.png" title="Skiing"></PlaceListItem>
      <PlaceListItem file_name="tropical.png" title="Tropical"></PlaceListItem>
    </div>
    <p class="font-bold text-[32px] text-white mt-16 ml-[12.25rem]">
      Top Vacation Destinations
    </p>
    <SlideDestination></SlideDestination>
    <Offer></Offer>
    <Property></Property>
    <Plan></Plan>
    <Community></Community>
    <Contact></Contact>
    <Footer></Footer>
  </div>
</template>

<script>
import SlideDestination from "@/components/layout/SlideDestination";
export default {
  name: 'IndexPage',
  components: {SlideDestination}
}
</script>

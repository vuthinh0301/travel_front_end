<template>
  <div>
    <img :src="require(`@/assets/place/${file_name}`)" class="w-8 h-8 mx-auto">
    <div class="mt-4">
      <a href="#" class="text-white/40">{{title}}</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "PlaceListItem",
  props: {
    file_name:{
      type: String,
      require: true
    },
    title: {
      type: String,
      require: true
    },
    isBold: {
      type: Boolean,
      default: false
    }
  }
}
</script>

<style scoped>

</style>

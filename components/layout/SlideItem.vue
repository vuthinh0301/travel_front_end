<template>
    <div class="relative z-20 min-w-[19.375rem]">
      <img :src="require(`@/assets/${destination}`)" class="z-20 rounded-lg">
      <span class="absolute bottom-6 left-6 text-white font-medium text-2xl">{{ info }}</span>
    </div>
</template>

<script>
export default {
  name: "SlideItem",
  props: {
    destination: {
      type: String,
      require: true
    },
    info: {
      type: String,
      require: true
    }
  }
}
</script>

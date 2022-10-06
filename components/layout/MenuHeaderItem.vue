<template>
  <a href="#" class="p-2 text-base font-sans leading-4 text-white text-opacity-70 my-6 hover:border-b" :class="isBold ? 'font-bold' : 'font-normal'">{{ title }}</a>
</template>

<script>
export default {
  name: "MenuHeaderItem",
  props: {
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


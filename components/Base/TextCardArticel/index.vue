<template>
  <div class="flex flex-col">
    <h4 class="font-bold text-2xl text-gray-900 mb-2">{{ title }}</h4>
    <p class="font-medium text-gray-700 text-lg mb-2">{{ description }}</p>
    <p class="text-gray-500 text-base font-medium">{{ date }}</p>
  </div>
</template>

<script>
export default {
  name: 'BaseTextCardArticel',
  props: {
    title: {
      type: String,
      default: '',
    },
    description: {
      type: String,
      default: '',
    },

    date: {
      type: String,
      default: '',
    },
  },
}
</script>

<style></style>

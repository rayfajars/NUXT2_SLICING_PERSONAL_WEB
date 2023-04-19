<template>
  <div class="w-[740px] h-[132px] flex gap-x-4">
    <div>
      <BaseIcon
        mode="image"
        :icon="`images/${images}`"
        :width="170"
        :height="132"
      />
    </div>
    <BaseTextCardArticel :title="title" :description="description" :date="date"/>
  </div>
</template>

<script>
export default {
  name: 'BaseSideCards',
  props: {
    title: {
      type: String,
      default: '',
    },
    description: {
      type: String,
      default: '',
    },
    images: {
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

<template>
  <div class="md:w-[740px] w-full md-h-[132px] h-full flex gap-x-4 flex-col md:flex-row gap-y-10">
    <div>
      <BaseIcon
        mode="image"
        :icon="`images/${images}`"
        class="md:!w-[170px] !h-[132px] !w-[327px]"
      />
    </div>
    <BaseTextCardArticel
      :title="title"
      :description="description"
      :date="date"
    />
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

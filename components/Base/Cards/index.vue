<template>
  <div class="h-[388px] w-[360px] mr-5">
    <div>
      <BaseIcon
        mode="image"
        :icon="`images/${images}`"
        width="360"
        height="280"
      />
    </div>
    <div>
      <h4 class="text-gray-900 font-bold text-2xl">{{ title }}</h4>
      <p class="text-gray-700 font-medium text-lg self-stretch">
        {{ description }}
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BaseCards',
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
  },
}
</script>

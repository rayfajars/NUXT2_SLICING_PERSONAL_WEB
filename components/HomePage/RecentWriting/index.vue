<template>

  <div class="md:container md:mx-auto mt-20 px-6 mx-6">
    <div class="md:container">
      <BaseTitle>Recent Writing</BaseTitle>
      <div class="mt-10 flex flex-col">
        <BaseTextCardArticel
          v-for="data in dataRecentWriting"
          :key="data.title"
          :title="data.title"
          :description="data.description"
          :date="data.date"
          class="mb-8"
        />
      </div>
      <div class="flex justify-center md:justify-normal mt-8">
        <button
          class="text-black font-bold text-center text-lg h-12 md:w-44 w-full border-2 border-solid border-black hover:bg-black hover:text-white hover:border-none transition-colors ease-in-out duration-300"
        >
          View all Posts
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePageRecentWriting',
  data() {
    return {
      dataRecentWriting: [
        {
          title: 'Vortals convergence TCP',
          description:
            'Iusto labore necessitatibus. Ut minima autem fuga ad eaque eos. Cumq...',
          date: 'Thu Jan 09, 2031',
        },
        {
          title: 'Unbranded navigate',
          description:
            'Veniam consequatur distinctio. Sit dicta non odit ut. Eum iure dolor in et odit. Consectetur quis ut sit ducimus...',
          date: 'Fri Jun 11, 2027',
        },
      ],
    }
  },
}
</script>

<style></style>

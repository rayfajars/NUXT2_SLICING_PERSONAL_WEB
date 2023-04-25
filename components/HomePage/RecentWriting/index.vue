<template>
  <!-- <div class="container mt-20">
    <div class="container">
      <BaseTitle>Recent Writing</BaseTitle>
      <BaseTextCardArticel
        v-for="data in dataRecentWriting"
        :key="data.title"
        :title="data.title"
        :description="data.description"
        :date="data.date"
        class="mt-10 mb-[64px]"
      />

      <button
        class="text-black font-bold text-center text-lg h-[48px] w-[234px] border-2 border-solid border-black hover:bg-black hover:text-white hover:border-none transition-colors ease-in-out duration-300"
      >
        View all Posts
      </button>
    </div>
  </div> -->

  <div class="container mx-auto mt-20 px-4">
    <BaseTitle class="text-center md:text-left">Recent Writing</BaseTitle>
    <div class="mt-10 grid gap-8 md:grid-cols-2 lg:grid-cols-3">
      <BaseTextCardArticel
        v-for="data in dataRecentWriting"
        :key="data.title"
        :title="data.title"
        :description="data.description"
        :date="data.date"
        class="mb-8"
      />
    </div>
    <div class="flex justify-center mt-8">
      <button
        class="text-black font-bold text-center text-lg h-12 w-44 border-2 border-solid border-black hover:bg-black hover:text-white hover:border-none transition-colors ease-in-out duration-300"
      >
        View all Posts
      </button>
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

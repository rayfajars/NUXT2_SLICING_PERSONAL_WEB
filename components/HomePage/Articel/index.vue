<template>
  <!-- <div class="container mt-16">
    <div class="container">
      <BaseTitle>Case Studies</BaseTitle>
      <div class="flex mt-10">
        <BaseCards
          v-for="data in dataCaseStudies"
          :key="data.title"
          :title="data.title"
          :description="data.description"
          :images="data.images"
        />
      </div>
    </div>
  </div> -->

  <div class="container mx-auto mt-16 px-4">
    <BaseTitle class="text-center md:text-left">Case Studies</BaseTitle>
    <div class="flex flex-wrap mt-10 justify-center md:justify-start">
      <BaseCards
        v-for="data in dataCaseStudies"
        :key="data.title"
        class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 px-2 mb-8"
        :title="data.title"
        :description="data.description"
        :images="data.images"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePageArticel',
  data() {
    return {
      dataCaseStudies: [
        {
          title: 'Float Life',
          description:
            'Iusto labore necessitatibus. Ut minima autem fuga ad eaque eos. Cumq...',
          images: 'image1.png',
        },
        {
          title: 'Retro Call',
          description:
            'Distinctio aperiam maiores et mollitia necessitatibus. Et reprehenderit.',
          images: 'image2.png',
        },
      ],
    }
  },
}
</script>

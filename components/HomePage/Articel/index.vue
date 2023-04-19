<template>
  <div class="container mt-16">
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

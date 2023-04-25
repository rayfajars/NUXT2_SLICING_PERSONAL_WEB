<template>
  <div>


    <div
      class="bg-black w-full h-[80px] flex items-center justify-center md:justify-start"
    >
      <div
        class="mx-auto md:m-auto flex flex-col md:flex-row md:items-center md:gap-x-16 gap-y-4"
      >
        <h5 class="text-white font-bold text-lg md:text-xl text-center">
          Find me across the internet:
        </h5>
        <div class="flex gap-x-12 md:gap-x-20">
          <a href="#" class="navbar-link"
            ><BaseIcon class="!bg-white" icon="icons/mail.svg"
          /></a>
          <a href="#" class="navbar-link"
            ><BaseIcon class="!bg-[#03A9F4]" icon="icons/twitter.svg"
          /></a>
          <a href="#" class="navbar-link"
            ><BaseIcon mode="image" icon="icons/linkedin.svg"
          /></a>
          <a href="#" class="navbar-link"
            ><BaseIcon mode="image" icon="icons/instagram.svg"
          /></a>
          <a href="#" class="navbar-link"
            ><BaseIcon class="!bg-white" icon="icons/github.svg"
          /></a>
          <a href="#" class="navbar-link"
            ><BaseIcon mode="image" icon="icons/drible.svg"
          /></a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePageFindMe',
}
</script>

<template>
  <div class="bg-black w-full h-[80px] flex">
    <div class="m-auto flex gap-x-16">
      <div>
        <h5 class="text-white font-bold text-lg">
          Find me across the internet:
        </h5>
      </div>
      <div class="flex gap-x-20">
        <a href="#" class="navbar-link "><BaseIcon class="!bg-white" icon="icons/mail.svg" /></a>
        <a href="#" class="navbar-link "><BaseIcon class="!bg-[#03A9F4]" icon="icons/twitter.svg" /></a>
        <a href="#" class="navbar-link "><BaseIcon mode="image" icon="icons/linkedin.svg" /></a>
        <a href="#" class="navbar-link "><BaseIcon mode="image" icon="icons/instagram.svg" /></a>
        <a href="#" class="navbar-link "><BaseIcon class="!bg-white" icon="icons/github.svg" /></a>
        <a href="#" class="navbar-link "><BaseIcon mode="image" icon="icons/drible.svg" /></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePageFindMe',
}
</script>

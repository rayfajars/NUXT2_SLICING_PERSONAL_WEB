<template>
  <footer
    class="bg-white py-4 md:py-6 shadow-sm w-full border-t-2 border-gray-200 mt-14 px-6 md:px-0"
  >
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="md:flex md:items-center md:justify-between">
        <div
          class="text-left md:text-center mb-4 md:mb-0 md:w-full w-[327px] flex flex-col md:flex-row gap-y-1"
        >
          <p class="text-gray-500 text-xs font-medium">Wade Wilson |&nbsp;</p>
          <p class="text-gray-500 text-xs font-medium">
            Feel free to drop a ‘hello’ @&nbsp;
          </p>
          <p class="text-gray-500 text-xs font-medium">wade@example.com</p>
        </div>
        <div class="flex gap-x-20 md:gap-x-14 md:justify-end">
          <a href="#" class="navbar-link"
            ><BaseIcon class="!bg-gray-400" icon="icons/mail.svg"
          /></a>
          <a href="#" class="navbar-link"
            ><BaseIcon class="!bg-gray-400" icon="icons/twitter.svg"
          /></a>
          <a href="#" class="navbar-link"
            ><BaseIcon class="!bg-gray-400" icon="icons/linkedin.svg"
          /></a>
          <a href="#" class="navbar-link"
            ><BaseIcon class="!bg-gray-400" icon="icons/github.svg"
          /></a>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'LayoutsFooter',
}
</script>

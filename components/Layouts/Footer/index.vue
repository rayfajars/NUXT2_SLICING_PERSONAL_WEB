<template>
  <footer class="bg-white py-6 shadow-sm w-full">
    <div class="flex justify-between container">
      <div>
        <p class="text-gray-500 text-xs font-medium">
          Wade Wilson | Feel free to drop a ‘hello’ @ wade@example.com
        </p>
      </div>
      <div class="flex gap-x-10">
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
  </footer>
</template>

<script>
export default {
  name: 'LayoutsFooter',
}
</script>

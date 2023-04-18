<template>
  <header class="py-6 bg-white container">
    <div class="flex items-center justify-between">
      <a href="#" class="text-black font-extrabold text-2xl">Wade.</a>

      <nav >
        <ul class="flex items-center gap-20">
          <li>
            <a href="#" class="navbar-link text-lg text-gray-900 font-bold"
              >Home</a
            >
          </li>
          <li>
            <a href="#" class="navbar-link text-gray-900 font-medium text-lg"
              >Blog</a
            >
          </li>
          <li>
            <a href="#" class="navbar-link text-gray-900 font-medium text-lg"
              >Work</a
            >
          </li>
          <li>
            <a href="#" class="navbar-link text-gray-900 font-medium text-lg"
              >About</a
            >
          </li>
        </ul>
      </nav>
      <div class="flex items-center gap-10">
        <a href="#" class="navbar-link "><BaseIcon class="!bg-gray-900" icon="icons/mail.svg" /></a>
        <a href="#" class="navbar-link "><BaseIcon class="!bg-gray-900" icon="icons/twitter.svg" /></a>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'LayoutsNavbar',
}
</script>

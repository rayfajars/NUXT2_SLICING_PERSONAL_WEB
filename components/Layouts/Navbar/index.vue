<template>
  <header class="py-4 md:py-6 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between">
        <a href="#" class="text-black font-extrabold text-xl sm:text-2xl"
          >Wade.</a
        >

        <!-- tambahkan tombol burger untuk mode responsif -->
        <div class="flex md:hidden">
          <button
            type="button"
            class="inline-flex items-center justify-center p-2 rounded-md text-black hover:text-gray-800 hover:bg-gray-200 focus:outline-none focus:bg-gray-200 focus:text-gray-800 transition duration-150 ease-in-out"
            aria-label="Menu"
            @click="toggleMenu"
          >
          <BaseIcon  icon="icons/Menu.svg" />
          </button>
        </div>

        <nav class="hidden md:block">
          <ul class="flex items-center gap-8">
            <li>
              <a
                href="#"
                class="text-lg font-bold text-gray-900 hover:text-gray-800 transition duration-150 ease-in-out"
                >Home</a
              >
            </li>
            <li>
              <a
                href="#"
                class="text-lg font-medium text-gray-900 hover:text-gray-800 transition duration-150 ease-in-out"
                >Blog</a
              >
            </li>
            <li>
              <a
                href="#"
                class="text-lg font-medium text-gray-900 hover:text-gray-800 transition duration-150 ease-in-out"
                >Work</a
              >
            </li>
            <li>
              <a
                href="#"
                class="text-lg font-medium text-gray-900 hover:text-gray-800 transition duration-150 ease-in-out"
                >About</a
              >
            </li>
          </ul>
        </nav>

        <div class="hidden md:flex items-center gap-x-12">
          <a
            href="#"
            class="text-gray-900 hover:text-gray-800 transition duration-150 ease-in-out"
            ><BaseIcon class="!bg-gray-900" icon="icons/mail.svg"
          /></a>
          <a
            href="#"
            class="text-gray-900 hover:text-gray-800 transition duration-150 ease-in-out"
            ><BaseIcon class="!bg-gray-900" icon="icons/twitter.svg"
          /></a>
        </div>
      </div>
    </div>
    <!-- menu dropdown saat mode responsif -->
    <div v-show="menuOpen" class="md:hidden">
      <div class="px-2 pt-2 pb-3">
        <a
          href="#"
          class="block px-3 py-2 rounded-md text-base font-medium text-gray-900 hover:text-gray-800 hover:bg-gray-200 focus:outline-none focus:text-gray-800 focus:bg-gray-200 transitionduration-150 ease-in-out"
          >Home</a
        >
        <a
          href="#"
          class="mt-1 block px-3 py-2 rounded-md text-base font-medium text-gray-900 hover:text-gray-800 hover:bg-gray-200 focus:outline-none focus:text-gray-800 focus:bg-gray-200 transition duration-150 ease-in-out"
          >Blog</a
        >
        <a
          href="#"
          class="mt-1 block px-3 py-2 rounded-md text-base font-medium text-gray-900 hover:text-gray-800 hover:bg-gray-200 focus:outline-none focus:text-gray-800 focus:bg-gray-200 transition duration-150 ease-in-out"
          >Work</a
        >
        <a
          href="#"
          class="mt-1 block px-3 py-2 rounded-md text-base font-medium text-gray-900 hover:text-gray-800 hover:bg-gray-200 focus:outline-none focus:text-gray-800 focus:bg-gray-200 transition duration-150 ease-in-out"
          >About</a
        >
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'LayoutsNavbar',
  data() {
    return {
      menuOpen: false,
    }
  },
  methods: {
    toggleMenu() {
      this.menuOpen = !this.menuOpen
    },
  },
}
</script>

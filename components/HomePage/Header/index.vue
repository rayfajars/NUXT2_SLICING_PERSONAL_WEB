<template>
  <div class="bg-[#0085FF] w-full h-[500px] flex flex-col justify-center">
    <div class="mx-auto text-center px-6 md:px-0">
      <h1 class="text-gray-900 font-black text-[48px] md:text-[64px] leading-[75px] mb-6">
        Wade Wilson
      </h1>
      <div
        class="w-full max-w-md mx-auto mb-10 md:w-[670px] md:h-[84px] md:max-w-none"
      >
        <p class="text-gray-900 font-bold leading-[28px] md:text-xl text-lg">
          Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
          sint. Velit officia consequat duis enim velit mollit. Exercitation
          veniam consequat sunt nostrud amet.
        </p>
      </div>
      <div
        class="mt-auto mb-4 flex flex-col md:flex-row md:justify-center gap-y-4 md:gap-10"
      >
        <button
          class="text-white bg-black font-bold text-center text-lg h-12 md:h-[48px] w-full md:w-[234px] hover:bg-transparent hover:text-gray-900 hover:border-2 hover:border-solid hover:border-gray-900 transition-colors ease-in-out duration-300 mb-4 md:mb-0"
        >
          View my works
        </button>
        <button
          class="text-gray-900 font-bold text-center text-lg h-12 md:h-[48px] w-full md:w-[234px] border-2 border-solid border-gray-900 hover:bg-black hover:text-white hover:border-none transition-colors ease-in-out duration-300"
        >
          Read more about me
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePageHeader',
}
</script>

<template>
  <div class="bg-[#0085FF] w-full h-[500px] flex">
    <div class="m-auto text-center">
      <h1 class="text-gray-900 font-extrabold text-[64px] leading-[75px] mb-6">
        Wade Wilson
      </h1>
      <div class="w-[670px] h-[84px] mb-10">
        <p class="text-gray-900 font-bold leading-[28px] text-xl">
          Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
          sint. Velit officia consequat duis enim velit mollit. Exercitation
          veniam consequat sunt nostrud amet.
        </p>
      </div>
      <div class="flex justify-center gap-10">
        <button
          class="text-white bg-black font-bold text-center text-lg h-[48px] w-[234px] hover:bg-transparent hover:text-gray-900 hover:border-2 hover:border-solid hover:border-gray-900 transition-colors ease-in-out duration-300"
        >
          View my works
        </button>
        <button
          class="text-gray-900 font-bold text-center text-lg h-[48px] w-[234px] border-2 border-solid border-gray-900 hover:bg-black hover:text-white hover:border-none transition-colors ease-in-out duration-300"
        >
          Read more about me
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LayoutsHeader',
}
</script>

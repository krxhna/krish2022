<template>
  <div class="flex flex-col justify-center h-screen items-center ">
    <img class="w-[90vw] my-2 absolute " src="https://firebasestorage.googleapis.com/v0/b/greenlines-69a5c.appspot.com/o/15.png?alt=media&token=50dd54f6-52c4-4250-9606-8566879385db" />

    <div class="relative text-center">
      <div class="text-4xl capitalize  m-3 w-screen font-sans font-semibold mx-4">
        <div
          class="font-bold text-6xl"
        >
          Krishna Kanth
        </div>

        <div class=" items-center flex justify-center">
        
        <div class="w-96 text-base m-3 text-left p-3 border border-gray-100 rounded-md overflow-hidden shadow-lg backdrop-blur-sm">
        I'm a software engineer and artist based in Toronto. I have great interest in full-stack development, artificial intelligence, human-computer interactions, and everything in between.
          <span
    class="absolute inset-x-0 bottom-0 h-2  bg-gradient-to-r from-green-300 via-blue-500 to-purple-600"
  ></span>
        </div>
        
        </div>
      </div>

    </div>

<a
  class="relative block  p-8 overflow-hidden border border-gray-100 rounded-lg"
  href=""
>
  <span
    class="absolute inset-x-0 bottom-0 h-2  bg-gradient-to-r from-green-300 via-blue-500 to-purple-600"
  ></span>

  <div class="justify-between sm:flex">
    <div>
      <h5 class="text-xl font-bold text-gray-900">
        Building a SaaS product as a software developer
      </h5>
      <p class="mt-1 text-xs font-medium text-gray-600">By John Doe</p>
    </div>

    <div class="flex-shrink-0 hidden ml-3 sm:block">
      <img
        class="object-cover w-16 h-16 rounded-lg shadow-sm"
        src="https://www.hyperui.dev/photos/man-5.jpeg"
        alt=""
      />
    </div>
  </div>

  <div class="mt-4 sm:pr-8">
    <p class="text-sm text-gray-500">
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. At velit illum
      provident a, ipsa maiores deleniti consectetur nobis et eaque.
    </p>
  </div>

  <dl class="flex mt-6">
    <div class="flex flex-col-reverse">
      <dt class="text-sm font-medium text-gray-600">Published</dt>
      <dd class="text-xs text-gray-500">31st June, 2021</dd>
    </div>

    <div class="flex flex-col-reverse ml-3 sm:ml-6">
      <dt class="text-sm font-medium text-gray-600">Reading time</dt>
      <dd class="text-xs text-gray-500">3 minute</dd>
    </div>
  </dl>
</a>



    <!-- <bottomnavbarVue :ticker="ticker" class="fixed bottom-0"></bottomnavbarVue> -->
  </div>
</template>

<script>
// import bottomnavbarVue from "../components/bottomnavbar.vue";

export default {
  components: {
    // bottomnavbarVue,
  },

  props: ["ticker"],
};
</script>

<style lang="scss" scoped></style>

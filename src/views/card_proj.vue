<template>
  <div class="items-center flex flex-col justify-center cursor-default group ">
    <div
      class="w-96  text-base m-3 text-left p-3 border border-gray-100 rounded-md  hover:-translate-y-4 transition-all ease-in  overflow-hidden shadow-lg backdrop-blur-2xl "
    >
      <div class="text-3xl p-2 flex justify-between">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-6"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M8 9l3 3-3 3m5 0h3M5 20h14a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"
          />
        </svg>
        <!-- second part with github logo and external link -->
        <div class="flex gap-2">
        <!-- //github -->
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            class="h-6 w-6  scale-105 transition-all cursor-pointer hover:fill-purple-500 hover:scale-105"
            viewBox="0 0 24 24"
          >
            <path
              d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"
            />
          </svg>

          <!-- link -->
          <svg


            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6 hover:stroke-purple-500 scale-105 transition-all cursor-pointer"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            stroke-width="2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
            />
          </svg>
        </div>
      </div>
      <div class="text-3xl">{{ title1 }}</div>
      <div class="  mt-2 text-black">
       {{description}}
      </div>

      <div class="my-3 text-sm font-normal">
        {{ tech }}
      </div>

      <span
        class="absolute inset-x-0 bottom-0 h-2 bg-gradient-to-r from-green-300 via-blue-500 to-purple-600  transition-all ease-in-out"
      ></span>
    </div>
  </div>
</template>


// to do 

// add link to github  and link 

// add desc as props


<script>
export default {
  props: ["title1", "description", "tech"],

  data() {
    return {
      // changed fooo and bar to items
      items: [
        { message: "javascript" },
        { message: "python" },
        { message: "vue" },
        { message: "nodeJS" },
        { message: "flutter" },
        { message: "CSS" },
        { message: "HTML5" },
      ],
    };
  },
};
</script>

<style lang="scss" scoped></style>

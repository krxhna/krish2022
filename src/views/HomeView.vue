<template>
  <div class="flex flex-col justify-center h-screen items-center mt-32">
    <img
      class="md:w-[90vw] my-2 fixed"
      src="https://firebasestorage.googleapis.com/v0/b/greenlines-69a5c.appspot.com/o/15.png?alt=media&token=50dd54f6-52c4-4250-9606-8566879385db"
    />

    <div class="relative text-center w-screen h-full">
      <div
        class="text-4xl capitalize m-3 w-screen font-sans font-semibold mx-4"
      >
        <div class="flex justify-start flex-col">
          <div class="font-bold text-6xl ml-4">Krishna Kanth</div>

          <cardVue></cardVue>
        </div>

        <div class="p-5 border-2">
          <div class="d m-3">/ software-creations</div>

          <div class="grid md:grid-cols-2 lg:grid-cols-3">
            <card_projVue
              title1="Greenlines.pro"
              description="A web application helping investors to spend up investment research and workflow by upto 30 times involving charts,news notes and more. access to everythign one click"
              tech="vue.js, tailwindcss, Firebase Auth, Node, ExpressJS, MongoDB"
            ></card_projVue>
            <card_projVue
              title1="By Culture"
              description="Web based app to help find the best companies with the best people, by matching them with culture, and values of the compnay so people have have happy meaningfull work and meaningful relationships"
              tech="Nuxt.js, tailwindcss"
            ></card_projVue>
            <card_projVue title1="Daisy fitness" 
            
            description="A web application to help people to manage their fitness and health by tracking their progress and helping them to achieve their goals, using science backed physcolgy based methods for long term results"
            
            tech="vue,js"></card_projVue>
            <!-- <card_projVue title1="Dee" tech="vue,js"></card_projVue> -->
            <!-- <card_projVue></card_projVue>
        <card_projVue></card_projVue> -->
          </div>
        </div>
      </div>
    </div>

    <div class="fixed flex top-4 right-5 gap-2 items-center">
      <a
        class="flex gap-2 capitalize"
        target="_blank"
        href="https://github.com/krxhna"
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          class="h-6 w-6 transition-all cursor-pointer hover:fill-purple-500 hover:scale-105"
          viewBox="0 0 24 24"
        >
          <path
            d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"
          />
        </svg>
      </a>
      <a class="flex gap-1 capitalize" href="mailto:krishhkrishhk@gmail.com"
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-7 w-7 hover:stroke-purple-500 hover:scale-105"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="2"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
          />
        </svg>
      </a>
    </div>

    <!-- <bottomnavbarVue :ticker="ticker" class="fixed bottom-0"></bottomnavbarVue> -->
  </div>
</template>

<script>
// import bottomnavbarVue from "../components/bottomnavbar.vue";
import cardVue from "../components/card.vue";
import card_projVue from "./card_proj.vue";

export default {
  components: {
    cardVue,
    card_projVue,
    // bottomnavbarVue,
  },

  data() {
    return {
      ticker: 0,
    };
  },
};
</script>

<style lang="scss" scoped></style>

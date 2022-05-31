<template>
  <div class="flex flex-col justify-center h-screen items-center ">
    <img class="w-[90vw] my-2 fixed " src="https://firebasestorage.googleapis.com/v0/b/greenlines-69a5c.appspot.com/o/15.png?alt=media&token=50dd54f6-52c4-4250-9606-8566879385db" />

    <div class="relative text-center w-screen h-full ">
      <div class="text-4xl capitalize  m-3 w-screen font-sans font-semibold mx-4">
        <div
          class="font-bold text-6xl"
        >
          Krishna Kanth
        </div>

        <cardVue></cardVue>


        <div class="d">software-creations</div>


        <div class="p-5 border-2 backdrop-blur-lg grid grid-cols-3">
        
                <cardVue></cardVue>
        <cardVue></cardVue>
                <cardVue></cardVue>
        <cardVue></cardVue>
        
        </div>


        


        
      </div>

    </div>



    <!-- <bottomnavbarVue :ticker="ticker" class="fixed bottom-0"></bottomnavbarVue> -->
  </div>
</template>

<script>
// import bottomnavbarVue from "../components/bottomnavbar.vue";
import cardVue from '../components/card.vue';



export default {
  components: {
    cardVue
    // bottomnavbarVue,
  },

  props: ["ticker"],
};
</script>

<style lang="scss" scoped></style>

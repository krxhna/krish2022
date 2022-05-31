<template>
  <div class="bg-slate-100">
    <div class="m-20">
      <div class="text-3xl italic font-semibold text-yellow-600">
        hola mi amigos 🌮
      </div>

      <div class="text-xl italic">skills i got</div>

      <!-- copy pasted from  https://vuejs.org/guide/essentials/list.html#v-for -->
      <li v-for="item in items">🌮{{ item.message }}</li>
    </div>
    <div class="d">github</div>
  </div>
</template>

<script>
export default {
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

<style></style>

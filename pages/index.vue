<template>
  <div class="w-screen h-screen bg-zinc-900 flex justify-between items-center flex-col overflow-hidden">
    <Header_main />
    <div class="h-full w-[140vh] flex flex-col justify-center gap-20">
      <div class="h-fit w-[100vh] text-7xl text-white">
        Welcome to Blokio a new chatting website to stay communicated with your
        friends
      </div>
      <button class="h-20 w-72 bg-gray-500 rounded-2xl text-white text-2xl">Create Account</button>
    </div>
    <Footer_main />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Header_main from "~/layouts/Header_main.vue";
import Footer_main from "~/layouts/Footer_main.vue";

export default Vue.extend({
  name: "IndexPage",
  components: {
    Header_main,
    Footer_main,
  },
  head() {
    return {
      title: "Blokio",
      meta: [
        {
          hid: "Chatting Website",
          name: "Blokio a chatting website",
          content:
            "information about the purpose of the website and how to sign up",
          keywords: "Blokio, Chatting, Chatting Website",
        },
      ],
    };
  },
});
</script>

<style></style>

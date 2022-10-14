<template>
  <div class="w-screen h-screen bg-zinc-900 flex justify-center items-center">
    <div class="h-[75vh] w-[50vh] bg-zinc-600 rounded-[40px] flex items-center flex-col overflow-hidden">
      <div class="w-[50vh] h-20 bg-blue-500 mb-20"></div>
      <h1 class="text-4xl text-white underline mb-20">Reset Password</h1>
      <h2 class="w-[32vh] text-white text-2xl mb-3">Email:</h2>
      <input class="border-none h-14 w-[32vh] rounded-3xl mb-3" />
      <div class="text-white text-lg mb-8 cursor-pointer">Login</div>
      <button class="w-40 h-16 bg-gray-400 rounded-2xl text-white text-lg mb-auto cursor-pointer">Reset Password</button>
      <div class="w-[50vh] h-8 bg-blue-500 flex justify-center items-center"></div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  head() {
    return {
      title: "Blokio/Forgot Password",
    }
  }
})
</script>

<style scoped>

</style>
<template>
  <div class=" w-screen h-screen bg-zinc-900 flex justify-center items-center">
    <div class=" h-[75vh] w-[50vh] bg-zinc-600 rounded-[40px] flex items-center flex-col overflow-hidden">
      <div class="w-[50vh] h-20 bg-blue-500 mb-8"></div>
      <h1 class=" text-5xl text-white underline mb-16">Login</h1>
      <h2 class="w-[32vh] text-white text-2xl mb-3">Email:</h2>
      <input class=" border-none h-14 w-[32vh] rounded-3xl mb-3"/>
      <h2 class="w-[32vh] text-white text-2xl mb-3">Password:</h2>
      <input class=" border-none h-14 w-[32vh] rounded-3xl mb-3"/>
      <div class=" text-white text-xl mb-10 cursor-pointer">Forgot Password?</div>
      <button class=" w-40 h-12 bg-gray-400 rounded-2xl text-white text-lg mb-28 cursor-pointer">Login</button>
      <div class="w-[50vh] h-8 bg-blue-500 flex justify-center items-center">
        <div class=" text-white text-lg cursor-pointer">Create an Acoount</div>
      </div>
    </div>
  </div>
</template>


<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  head() {
    return {
      title: "Blokio/Login",
    }
  }
})
</script>

<style scoped>

</style>
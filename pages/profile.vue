<template>
  <div class="h-screen w-screen bg-zinc-900 flex flex-col justify-center items-center">
    <Header_main/>
    <div class="h-full w-full flex justify-center items-center">
      <div class=" h-[85vh] w-[120vh] bg-zinc-800 rounded-2xl flex flex-col justify-start items-center gap-5 pt-5">
        <div class="h-10 w-[100vh]  flex flex-row justify-start items-center gap-4 mb-2">
          <button class="h-10 w-10 rounded-full bg-blue-500 flex justify-center items-center">
            <svg class=" h-7 w-7 fill-blue-300 stroke-blue-300" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" xmlns:v="https://vecta.io/nano"><path d="M17.1 53l52.4-34.5v63z" stroke-miterlimit="10"/></svg>
          </button>
          <h1 class="text-white text-2xl">Profile</h1>
        </div>
        <div class=" h-10 w-[100vh] border-b-zinc-900 border-b-2 flex justify-start items-center text-white text-xl">Audio / Video</div>
        <div class=" h-20 w-[100vh]  flex justify-between items-center gap-10">
          <div class=" h-20 w-40 flex flex-col gap-2">
            <h2 class="text-white text-xl">Microphone</h2>
            <select name="microphones" class=" w-40 h-8 bg-zinc-600"></select>
          </div>
          <div class=" h-20 w-40 flex flex-col gap-2 ">
            <h2 class="text-white text-xl">Audio</h2>
            <select name="microphones" class="w-40 h-8 bg-zinc-600"></select>
          </div>
          <div class=" h-20 w-40 flex flex-col gap-2 ">
            <h2 class="text-white text-xl">Video</h2>
            <select name="microphones" class="w-40 h-8 bg-zinc-600"></select>
          </div>
        </div>
        <div class=" h-10 w-[100vh] border-b-zinc-900 border-b-2 flex justify-start items-center text-white text-xl">Appearence</div>
        <div class="h-20 w-[100vh] flex gap-2 items-center">
          <div class="h-10 w-10 bg-white rounded-full"></div>
          <button class="h-10 w-40 bg-zinc-600 text-white">Upload Image</button>
        </div>
        <div class="h-20 w-[100vh] flex flex-row justify-start items-center gap-5">
          <div class="h-12 w-36 bg-zinc-600 flex justify-center items-center text-white">Message Size</div>
          <div class=" flex justify-center items-center flex-col">
            <div class="w-[80vh] flex justify-center items-center gap-20">
              <span class="text-white h-5 w-24 flex justify-center items-center">Extra Small</span>
              <span class="text-white h-5 w-24 flex justify-center items-center">Small</span>
              <span class="text-white h-5 w-24 flex justify-center items-center">Medium</span>
              <span class="text-white h-5 w-24 flex justify-center items-center">large</span>
              <span class="text-white h-5 w-24 flex justify-center items-center">Extra Large</span>
            </div>
            <input class=" w-[75vh] bg-zinc-500" type="range" min="0" max="4">
          </div>
        </div>
        <div class="h-20 w-[100vh] flex flex-row justify-start items-center gap-5">
          <div class="h-12 w-44 bg-zinc-600 flex justify-center items-center text-white">Message Orientation</div>
          <diV class=" h-20 w-72  flex justify-between items-center">
            <button class=" h-16 w-16 bg-zinc-600">
              <svg class=" fill-zinc-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 500" stroke="#000" stroke-miterlimit="10" xmlns:v="https://vecta.io/nano"><path d="M17 27.1h261.3V49H17zm0 77h249.5V126H17zm0-38.5h186.1v21.9H17zm0 135.2h261.3v21.9H17zm0 77h249.5v21.9H17zm0-38.5h186.1v21.9H17zm0 135.1h261.3v21.9H17zm0 77.1h249.5v21.9H17zm0-38.5h186.1v21.9H17z"/></svg>
            </button>
            <button class="h-16 w-16 bg-zinc-600">
              <svg class=" fill-zinc-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 500" stroke="#000" stroke-miterlimit="10" xmlns:v="https://vecta.io/nano"><path d="M14 26.4h261.3v21.9H14zm0 77h249.5v21.9H14zm0-38.5h186.1v21.9H14zm0 309.7h261.3v21.9H14zm0 77.1h249.5v21.9H14zm0-38.5h186.1v21.9H14zm210.2-212.7h261.3v21.9H224.2zm11.8 77.1h249.5v21.9H236zm63.5-38.1h186.1v21.9H299.5z"/></svg>
            </button>
            <button class="h-16 w-16 bg-zinc-600">
              <svg class=" fill-zinc-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 500" stroke="#000" stroke-miterlimit="10" xmlns:v="https://vecta.io/nano"><path d="M221.3 26.5h261.3v21.9H221.3zm11.8 77h249.5v21.9H233.1zm63.4-38h186.1v21.9H296.5zM221.3 200h261.3v21.9H221.3zm11.8 77.1h249.5V299H233.1zm63.4-38.1h186.1v21.9H296.5zm-75.2 134.6h261.3v21.9H221.3zm11.8 77h249.5v21.9H233.1zm63.4-38.1h186.1v21.9H296.5z"/></svg>
            </button>
          </diV>
        </div>
      </div>
    </div>
    <Footer_main/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Header_main from "~/layouts/Header_main.vue"
import Footer_main from "~/layouts/Footer_main.vue"
export default Vue.extend({
  components: {
    Header_main,
    Footer_main,
  }
})
</script>

<style scoped>

</style>
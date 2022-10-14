<template>
  <div class=" bg-blue-500 w-screen h-16 flex items-center flex-row gap-5 pl-4">
    <div class="w-10 h-10 bg-blue-200"></div>
    <div class="text-white flex items-center mr-auto text-2xl">Blokio</div>
    <div  class="h-full w-40 bg-blue-300 flex justify-center items-center text-white cursor-pointer" >Go to Dashboard</div>
    <div  class=" w-10 h-10 bg-blue-200 rounded-full mr-5 hidden"></div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: "Header_main",
  props: {
    dashboard_vis: {
      type: String,
      default: "none",
    },
    profile_vis: {
      type: String,
      default: "none",
    },
  },
  computed: {
    dashboard_style() {
      return {display: this.dashboard_vis}
    },
    profile_style() {
      return {"background-color": this.profile_vis}
    },
  },
})
</script>

<style>

</style>
<template>
  <div class="flex justify-evenly items-center text-xs font-black text-gray-500 p-10">
    <router-link to="/" class="hover:bg-green-700 uppercase text-white text-xl name-link rounded-full p-2">JM Acera</router-link>
    <ul class="flex">
      <li class=""><router-link to="/" class="hover:underline p-6 uppercase">Home</router-link></li>
      <li class=""><router-link to="/about" class="hover:underline p-6 uppercase">About Me</router-link></li>
      <li class=""><router-link to="/portfolio" class="hover:underline p-6 uppercase">Portfolio</router-link></li>
      <li class=""><router-link to="/contact" class="hover:underline p-6 uppercase">Contact</router-link></li>
    </ul>
  </div>
</template>

<script lang='ts'>
export default {
  name: 'Taskbar',
}
</script>

<style scoped>
  .name-link {
    background-color: #01a2a6;
  }
  .name-link:hover {
    opacity: 0.8;
  }
</style>
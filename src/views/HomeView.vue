<template>
  <div class="home">
    <Sidebar class=" fixed left-0 top-0 bottom-0 w-1/5"/>
    <div class="body">
      <img alt="Vue logo" src="../assets/logo.png">
      <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import Sidebar from '@/components/Sidebar/Sidebar.vue';

export default defineComponent({
  name: 'HomeView',
  components: {
    HelloWorld,
    Sidebar,
  },
});
</script>

<style lang="scss">
  .body {
    margin-left: 20%;
  }
</style>

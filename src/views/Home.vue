<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <MaterialUI/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import MaterialUI from '@/components/material-ui.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
    MaterialUI
  }
}
</script>

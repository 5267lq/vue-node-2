<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <NButton type="info">Info</NButton>
    <NButton type="success">Success</NButton>
    <Button type="warning">Warning</Button>
    <Button type="error">Error</Button>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import {Button} from 'view-design';
import Vue from 'vue';
Vue.component('NButton',Button);

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

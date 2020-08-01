<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Home msg="Bem vindo ao YouTube Trailers"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Home from '@/components/Home.vue';
//import axios from "axios"

export default {
  methods: {
  },
  name: 'Home',
  components: {
    Home
  }
}
</script>

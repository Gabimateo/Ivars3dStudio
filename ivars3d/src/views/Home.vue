<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <NavBar msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/NavBar.vue'

export default {
  name: 'Home',
  components: {
    NavBar
  }
}
</script>

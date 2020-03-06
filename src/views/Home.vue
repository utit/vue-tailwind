<template>
  <div class="home">
    <div class="mx-auto h-full flex justify-center items-center">
      <img class="" alt="Vue logo" src="../assets/logo.png">  
    </div>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

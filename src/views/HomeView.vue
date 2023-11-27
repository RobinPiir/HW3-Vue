<template>
  <div class="home">
    <WebHeader/>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <WebFooter/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import WebFooter from '@/components/footer.vue'
import WebHeader from '@/components/header.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    WebFooter,
    WebHeader
  }
}
</script>

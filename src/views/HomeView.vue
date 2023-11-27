<template>
  <div class="home">
    <WebHeader/>
    <img alt="Vue logo" src="../assets/logo.png">
    <PostsCompo/>
    <WebFooter/>
  </div>
</template>

<script>
// @ is an alias to /src
import WebFooter from '@/components/footer.vue'
import WebHeader from '@/components/header.vue'
import PostsCompo from '@/components/PostsCompo.vue'

export default {
  name: 'HomeView',
  components: {
    WebFooter,
    WebHeader,
    PostsCompo
  }
}
</script>

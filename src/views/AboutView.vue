<template>
  <div class="about">
    <WebHeader/>
    <h1>This is an about page</h1>
    <WebFooter/>
  </div>
</template>

<script>
// @ is an alias to /src
import WebFooter from '@/components/footer.vue'
import WebHeader from '@/components/header.vue'

export default {
  name: 'AboutView',
  components: {
    WebFooter,
    WebHeader
  }
}
</script>

<template>
  <div class="about">
    <HeaderCompo/>
    <h1>This is an about page</h1>
    <FooterCompo/>
  </div>
</template>

<script>
// @ is an alias to /src
import FooterCompo from '@/components/FooterCompo.vue'
import HeaderCompo from '@/components/HeaderCompo.vue'

export default {
  name: 'AboutView',
  components: {
    FooterCompo,
    HeaderCompo
  }
}
</script>

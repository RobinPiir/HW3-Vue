<template>
  <HeaderCompo/>
    <FooterCompo/>
</template>

<script>
// @ is an alias to /src
import FooterCompo from '@/components/FooterCompo.vue'
import HeaderCompo from '@/components/HeaderCompo.vue'

export default {
  name: 'HomeView',
  components: {
    FooterCompo,
    HeaderCompo,
  }
}
</script>

<template>
  <fragment>
    <Header />
    <Footer />
  </fragment>
</template>

<script>
import Header from '@/components/Header/Main';
import Footer from '@/components/Footer/Main';
import Body from '@/components/Main/Main';
import Fragment from 'vue-fragment'
export default {
  name: 'Index',
  components: {
    Header,
    Body,
    Footer,
  },
  data () {
    return {
      msg: 'Main infomation'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
html {
  height: 100%;
}
</style>

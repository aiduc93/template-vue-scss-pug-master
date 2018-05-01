<template lang="pug">
  #app
    img(src="./assets/images/logo.png")
    h1 {{msg}}
    <test></test>
</template>

<script >
  import Test from './components/test.vue';
  export default {
    name: 'app',
    components: {
      'test': Test
    },
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

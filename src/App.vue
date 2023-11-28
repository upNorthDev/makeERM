<template>
  <Playground msg="Welcome to Your Vue.js + TypeScript App"/>
  <Footer/>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import Playground from './components/Playground.vue';
import Footer from './components/Footer.vue';

@Options({
  components: {
    Playground,
    Footer
  },
})
export default class App extends Vue {}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>

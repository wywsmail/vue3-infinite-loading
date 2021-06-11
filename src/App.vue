<template>
  <HackerNews />
</template>

<script>
import { defineComponent, ref } from 'vue'
import HackerNews from './components/HackerNews.vue';

export default defineComponent({
  components: { HackerNews },
  setup() {
    const message = ref('hello world')

    return {
      message
    }
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
}
</style>

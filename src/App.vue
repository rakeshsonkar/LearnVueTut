<template>
<h1>Main</h1>
<TemplateView />
</template>

<script>
import TemplateView from './components/Test/TemplateView.vue'
export default {
  name: 'App',
  components: {
    TemplateView
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

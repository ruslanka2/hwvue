<template>
  
  <IndexComponents/>
  <BlogComponents/>
  <BlogdetalisComponents/>
</template>

<script>

import IndexComponents from './components/IndexComponents.vue';
import BlogComponents from './components/BlogComponents.vue';
import BlogdetalisComponents from './components/BlogdetalisComponents.vue';


export default {
  name: 'App',
  components: {
    IndexComponents,
    BlogComponents,
    BlogdetalisComponents
}
}
</script>

<style lang="scss">
#app {
  
}
</style>

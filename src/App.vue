<template>
  <IndexComponents/>
  <BlogComponents/>
  <BlogdetalisComponents/>
  <ProductDetalisComponents/>
</template>

<script>

import IndexComponents from './components/IndexComponents.vue';
import BlogComponents from './components/BlogComponents.vue';
import BlogdetalisComponents from './components/BlogdetalisComponents.vue';
import ProductDetalisComponents from './components/ProductDetalisComponents.vue';


export default {
  name: 'App',
  components: {
    IndexComponents,
    BlogComponents,
    BlogdetalisComponents,
    ProductDetalisComponents
}
}
</script>

<style lang="scss">
#app {
  
}
</style>

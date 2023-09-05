<template>
  <IndexComponents/>
  <BlogComponents/>
  <BlogdetalisComponents/>

 <CategoryComponents/>
</template>

<script>

import IndexComponents from './components/IndexComponents.vue';
import BlogComponents from './components/BlogComponents.vue';
import BlogdetalisComponents from './components/BlogdetalisComponents.vue';

import CategoryComponents from './components/CategoryComponents.vue';


export default {
  name: 'App',
  components: {
    IndexComponents,
    BlogComponents,
    BlogdetalisComponents,
   
    CategoryComponents
}
}
</script>

<style lang="scss">
#app {
  
}
</style>

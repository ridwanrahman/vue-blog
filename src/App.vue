<template>
  <div id="app">
    <show-blogs></show-blogs>
  </div>
</template>

<script>
import addBlog from './components/addBlog.vue';
import showBlogs from './components/showBlogs.vue';


export default {
  name: 'app',
  components: {
    'add-blog': addBlog,
    'show-blogs': showBlogs
  },
  data () {
    return {
    }
  }
}
</script>

<style>
body {
  margin: 0;
  font-family: 'Nunito SemiBold';
}

</style>

<template>
  <div id="app">
    <!-- <AddBlog/> -->
    <ShowBlogs/>
    <!-- <router-view/> -->
  </div>
</template>

<script>
import AddBlog from './components/AddBlog.vue'
import ShowBlogs from './components/ShowBlogs.vue'

export default {
  name: 'App',
  components: {
    AddBlog,
    ShowBlogs
  }
}
</script>

<style>

</style>

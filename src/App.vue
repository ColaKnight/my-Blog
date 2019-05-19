<template>
  <div id="app">
    <AddBlog/>
    <!-- <router-view/> -->
  </div>
</template>

<script>
import AddBlog from './components/AddBlog.vue'
export default {
  name: 'App',
  components: {
    AddBlog
  }
}
</script>

<style>
#add-blog *{
  box-sizing: border-box;
}
#add-blog *{
  margin: 20px, auto;
  max-width: 600px;
  padding: 20px;
}
label{
  display: block;
  margin: 20px, 0, 10px;
}
input[text="text"], textarea, select{
  display: block;
  width: 100%;
  padding: 8px;
}
</style>

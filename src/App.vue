<template>
  <div id="app">
    <blog-header></blog-header>
    <router-view></router-view>

  </div>
</template>

<script>
import AddBlog from './components/AddBlog'
import ShowBlogs from './components/ShowBlogs'
import BlogHeader from './components/BlogHeader'

export default {
  name: 'app',
  components: {
    AddBlog,ShowBlogs,BlogHeader
  }
}
</script>

<style>
ul{
  list-style-type: none;
  text-align: center;
  margin: 0;
}
li{
  display: inline-block;
  margin: 0 10px;
}
</style>

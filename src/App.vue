<template>
  <div id="app">
    <HeaderBlog/>
    <PortoBlog/>
    <NavBlog/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HeaderBlog from './components/HeaderBlog.vue'
import PortoBlog from './components/PortoBlog.vue'
import NavBlog from './components/NavBlog.vue'


export default {
  name: 'App',
  components: {
    // HelloWorld
    HeaderBlog,
    PortoBlog,
    NavBlog
  }
}
</script>

<style lang="scss">
/* RESET E IMPOSTAZIONI GENERALI */

* {
    margin: 0px;
    border: 0px;
    padding: 0px;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

</style>

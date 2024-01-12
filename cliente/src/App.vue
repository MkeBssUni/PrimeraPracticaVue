<script setup>
  import Navbar from './components/Navbar.vue';
  import Sidebar from './components/Sidebar.vue';
  import BodyContent from './components/BodyContent.vue'
</script>

<template>
  <div id="app">
      <Navbar/>
      <div class="row">
        <div class="col">
          <Sidebar/>
        </div>
        <div class="col">
          <BodyContent/>
        </div>
      </div>
  </div>
</template>

<style scoped>
#app{
  background-color: #f2f2f2;
}
</style>

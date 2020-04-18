<template>
  <div id="app">
    <font-awesome-icon icon="user-secret" />
    <!-- App Header -->
    <div class="appHeader">
        <div class="pageTitle">Cards Mobile</div>
    </div>
    <!-- * App Header -->
    <Card/>
  </div>
</template>

<script>
import Card from './components/Card.vue'
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'

export default {
  name: 'App',
  components: {
    Card
  }
}
</script>

<style>
@import '/css/style.css';
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
#app {
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: 15px;
    line-height: 1.6rem;
    letter-spacing: 0.004em;
  margin-top: 30px;
}
</style>

<template>
 <navbar-comp/>
  

  <!-- <h1>This is above the routerView</h1> -->
  <router-view/>
  <!-- <h1>This is below the routerView</h1> -->
  <navbar-comp/>
</template>

<script>
import NavbarComp from './components/NavbarComp.vue';
export default{
  components:{
    NavbarComp
  }
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>

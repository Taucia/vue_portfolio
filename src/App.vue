<template>

  <HeaderComponent/>
  <div class="container min-vh-100 my-5">
    <router-view/>
  </div>
  <Footer></Footer>


</template>

<script>
import HeaderComponent from "./components/HeaderComponent.vue";
import Footer from "@/components/Footer.vue";

export default{
  components: {
    HeaderComponent,
    Footer,  }
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
body {
  min-width: 100vw;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

</style>

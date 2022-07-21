<template>
  <div class="pro">
    <div class="text">
      <h2><span>My </span>Projects</h2>
    </div>
  </div>
  <div  class="container">
    
        <div class="row">
      <Cards />   
    </div>
    </div>
    
   
    
  
</template>

<script>
import Cards from "../components/Cards.vue";
export default {
  components: {
    Cards,
  },
};
</script>

<style scoped>
.container{
    min-height: 50vh;

}
.pro.text {
  padding-bottom: 20px;
}

.pro h2 {
  font-size: 35px;
  /* color: var(--second-color); */
  padding-bottom: 20px;
}

.pro h2 span {
  color: #dcabdf;
}

</style>

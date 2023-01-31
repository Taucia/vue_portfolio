<template>
<section id="landing">
  <div class="container-fluid">
    <p class="text animation">Taucia Jackson❤</p>
</div>  
</section>

 

</template>
<script>
  
export default{
  
}
</script>
<style scoped>



body {
  padding: 20px;
  font-family: 'Inconsolata', monospace;

}

.text{
  color:#dfb3e2 ;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    border-right: 4px solid black;
    font-size: 180%;
    white-space: nowrap;
    overflow: hidden;
    text-decoration: underline;
    text-align: center; 
}

.animation{
  animation: typewriter 4s steps(15) 1s infinite both,
             blinkCursor 500ms steps(15) infinite;
}

@keyframes typewriter {
  from {
    width: 0;
  }
  to {
    width: 314px;
  }
}

@keyframes blinkCursor{
  from {
    border-right-color: black;
  }
  to {
    border-right-color: transparent;
  }
}

</style>
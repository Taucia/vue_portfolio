<template>

  <div class="container-fluid">
  <svg viewBox="  560 300">
    <symbol id="s-text">
      <text text-anchor="middle" x="20%" y="60%">Taucia Jackson</text>
    </symbol>
  

    <g class = "g-ants">
      <use xlink:href="#s-text" class="text-copy"></use>
      <use xlink:href="#s-text" class="text-copy"></use>
      <use xlink:href="#s-text" class="text-copy"></use>
      <use xlink:href="#s-text" class="text-copy"></use>
      <use xlink:href="#s-text" class="text-copy"></use>
    </g>
  </svg>
</div>  
 

</template>
<script>
export default{
    
}
</script>
<style scoped>
.container-fluid{
    padding: 0 !important;
    margin: 0 !important;
    color:orchid;
    background-size: cover;
    width: 100vw;
    height: 100vh;
    background-repeat: no-repeat;
    background-position: center;
} 
/* @import url(https://fonts.googleapis.com/css?family=Montserrat); */

html, body{
  height: 50%;
  font-weight: 200;
  margin: 0;
  padding: 0;
}

body{
  background: black;
  font-family: Arial;
}

.container {
  display: flex;
/*   border:1px solid red; */
  height: 80%;
  align-items: center;
}

svg {
    display: block;
    font: 10.5em 'Taucia Jackson';
    width: 2960px;
    height: 500px;
    margin: 0 auto;
    
    
    color: #c554a5;;
}

.text-copy {
    fill: none;
    stroke: rgb(175, 88, 179);
    stroke-dasharray: 6% 29%;
    stroke-width: 5px;
    stroke-dashoffset: 0%;
    animation: stroke-offset 5.5s infinite linear;
}

.text-copy:nth-child(1){
	stroke: #c554a5;
	animation-delay: -1;
}

.text-copy:nth-child(2){
	stroke:plum;
	animation-delay: -2s;
}

.text-copy:nth-child(3){
	stroke: black;
	animation-delay: -3s;
}

.text-copy:nth-child(4){
	stroke: #dcabdf;
	animation-delay: -4s;
}

.text-copy:nth-child(5){
	stroke: purple;
	animation-delay: -5s;
}

@keyframes stroke-offset{
	100% {stroke-dashoffset: -35%;}
}
</style>
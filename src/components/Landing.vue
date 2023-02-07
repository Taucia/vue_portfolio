<template>
<section id="landing">
  
    <!-- <p class="text animation">Taucia Jackson❤</p> -->
    <!-- <p class="large rise">TAUCIA JACKSON</p> -->

</section>

<div class="hero-banner">
  <div class="hero-banner__title" aria-hidden="true">TAUCIA JACKSON</div>
  <img class="hero-banner__image" src="https://i.postimg.cc/2y4PJLTk/pampas-white-azalea-wallpaper-1-wa-pam-di-aza-xxx-004-1-pro-sq-arcit18.jpg"/>
  <h1 class="hero-banner__title hero-banner__stroked-title">TAUCIA JACKSON</h1>
</div>

<div class="content">
  Aspiring Web-Developer
</div>


</template>
<script>
  
export default{
  
}
</script>
<style scoped>



/* body {
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
} */



/* body,
html {
	height: 100%;
	display: grid;
	background-color:white;
	font-family: "Audiowide", cursive;
	color: orchid;
}

p {
	margin: auto;
}

.large {
	font-size: 6rem;
}

.small {
	font-size: 3rem;
}

.rise {
	text-shadow: -0.01em -0.01em 0.01em black;
	animation: rise 2s ease-in-out 0.5s forwards;
}

@keyframes rise {
	to {
		text-shadow: 0em 0.01em orchid, 0em 0.02em black, 0em 0.02em 0.03em orchid,
			-0.01em 0.01em black, -0.02em 0.02em black, -0.03em 0.03em orchid,
			-0.04em 0.04em black, -0.01em -0.01em 0.03em black, -0.02em -0.02em 0.03em black,
			-0.03em -0.03em 0.03em black;
		transform: translateY(-0.025em) translateX(0.04em);
	}
}

.outline {
	background-clip: text;
	color:orchid;
	animation: outline 1s ease-in-out 1.5s forwards;
}

@keyframes outline {
	from {
		text-shadow: 0em -7em 10em orchid
	}
	to {
		text-shadow: 0 0.02em black, 0.02em 0 black, -0.02em 0 black, 0 -0.02em orchid;
	}
} */
.hero-banner {
	 align-items: center;
	 display: flex;
	 height: 100vh;
	 position: relative;
	 justify-content: center;
	 z-index: -1;
}
 .hero-banner__title {
	 color: orchid;
	 font-size: 100px;
	 font-weight: 700;
	 padding: 0 20px;
	 position: absolute;
	 text-align: center;
	 text-transform: uppercase;
}
 .hero-banner__stroked-title {
	 color: transparent;
	 -webkit-text-stroke: 2px #dcabdf;
	 text-transform: 2px white;
}
 .hero-banner__image {
	 border-radius: 20px;
	 position: fixed;
	 transform: rotate(-15deg);
	 width: 450px;
}
 .content {
	 background-color: #eaeaea;
	 font-size: 40px;
	 padding: 120px 80px;
	 height: 100vh;
}
 body {
	 background-color: #000;
	 font-family: Arial;
}
 * {
	 box-sizing: border-box;
}
</style>
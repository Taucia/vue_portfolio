<!-- <template>

  
  <div class="skills ">
        <div>
            <div class="text">
                <h2><span>My</span> Skills</h2>
                
            </div>
            
            <div class="skill-card row">
                <div class="card col-md">
                  <i class="fas fa-file-code"></i>
                   <h4>Technical Skills</h4>
                    <h4>HTML</h4>
                      <div class="progress">
                    <div
                      class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                    >
                      100%
                    </div>
                  </div>
                </div>
                
                <div class="card col-md">
                  <i class="fas fa-file-code"></i>
                   <h4>Technical Skills</h4>
                    <h4>BOOTSRTAP</h4>
                      <div class="progress">
                    <div
                      class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                    >
                      90%
                    </div>
                  </div>
                </div>
                
                <div class="card col-md">
                 <i class="fas fa-file-code"></i>
                  <h4>Technical Skills</h4>
                    <h4>MYSQL</h4>
                     <div class="progress">
                    <div
                      class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                    >
                      95%
                    </div>
                  </div>
                </div>
                
                <div class="card col-md">
                    <i class="fas fa-file-code"></i>
                     <h4>Technical Skills</h4>
                    <h4>CSS</h4>
                      <div class="progress">
                    <div
                      class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                    >
                      85%
                    </div>
                  </div>
                </div>
                
                <div class="card col-md">
                  <i class="fas fa-file-code"></i>
                   <h4>Technical Skills</h4>
                    <h4>Nodes.js</h4>
                      <div class="progress">
                    <div
                      class="progress-bar w-50 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                    >
                      70%
                    </div>
                  </div>
                </div>
                
                <div class="card col-md">
                    <i class="fas fa-file-code"></i>
                     <h4>Technical Skills</h4>
                    <h4>JavaScript</h4>
                      <div class="progress">
                    <div
                      class="progress-bar w-50 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                    >
                      60%
                    </div>
                  </div>
                </div>
                <div class="card col-md">
                    <i class="fas fa-file-code"></i>
                     <h4>Technical Skills</h4>
                    <h4>VUE</h4>
                     <div class="progress">
                    <div
                      class="progress-bar w-50 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                    >
                      50%
                    </div>
                  </div>
                </div>
                
                <div class="card col-md">
                  <i class="fas fa-file-code"></i>
                  <h4>Technical Skills</h4>
                    <h4>VUEX</h4>
                      <div class="progress">
                    <div
                      class="progress-bar w-50 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                    >
                      40%
                    </div>
                  </div>
                </div>
                
                <div class="card col-md">
                    <i class="fas fa-file-code"></i>
                    <h4>Soft Skills</h4>
                    <h4>COMMUNICATION</h4>
                    <div class="progress">
                    <div
                      class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                    >
                      100%
                    </div>
                  </div>
                  
                </div>
            
             <div class="card col-md">
                    <i class="fas fa-file-code"></i>
                    <h4>Soft Skills</h4>
                    <h4>SELF-MANAGEMENT</h4>
                    <div class="progress">
                    <div
                      class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                    >
                      99%
                    </div>
                  </div>
                </div>
            
             <div class="card col-md">
                    <i class="fas fa-file-code"></i>
                    <h4>Soft Skills</h4>
                    <h4>TIME-MANAGMENT</h4>
                      <div class="progress">
                    <div
                      class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                    >
                      100%
                    </div>
                  </div>
                </div>
                 <div class="card col-md">
                    <i class="fas fa-file-code"></i>
                    <h4>Soft Skills</h4>
                    <h4>AMBITIOUS</h4>
                     <div class="progress">
                    <div
                      class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                    >
                      100%
                    </div>
                  </div>
                </div>
            </div>
            <a href="#">See All Skills</a>
            </div>
        </div>


</template>

<script>
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { library } from '@fortawesome/fontawesome-svg-core'

/* import specific icons */
import { faUserSecret } from '@fortawesome/free-solid-svg-icons'

/* add icons to the library */
library.add(faUserSecret)
export default {
    components: {
        FontAwesomeIcon
    }
}
</script>

<style >
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    overflow-wrap: none;
}

:root {
    --main-color: #dcabdf;
    --second-color:white;
    --third-color: black;
    --bg-color: #dddddf;
    --main-grid: repeat(auto-fill, minmax(300px, 1fr));
    --main-padding: 40px;
}

body {
    font-family: 'Poppins', sans-serif;
}

#skills{
  overflow-x: hidden;
}

 .container {
    padding-left: 10px;
    padding-right: 80px;
    margin-left: auto;
    margin-right: 2px;
} 


/* @media (min-width: 768px) {
    .container {
        width: 750px;
    }
} */

@media (max-width: 1250px) {
    .container {
        width: 15em;
    }
}



/* @media (min-width: 1200px) {
    .container {
        width: 1170px;
    }
} */

@media screen and (max-width: 1250px) {
  .card {
   
    width: 93vw;
    position: relative;
    left: 0;
  }
}

.skills {
    padding-top: var(--main-padding);
    padding-bottom: var(--main-padding);
    /* background-color: var(--bg-color); */
    text-align: center;
}

.skills .text {
    padding-bottom: 20px;
}

.skills h2 {
    font-size: 35px;
    /* color: var(--second-color); */
    padding-bottom: 20px;
}

.skills h2 span {
    color: var(--main-color);
}



.skills .skill-card {
   position: relative;
    left: -3rem;
    display: grid;
    grid-template-columns: var(--main-grid);
    grid-gap: 60px;
    margin-bottom: 70px;
    margin-top: 60px;
}

.skills .skill-card .card{
    padding: 25px;
    text-align: center;
    background-color: var(--second-color);
    border: 2px solid var(--main-color);
    color: var(--third-color);
    transition: 1s;
    position: relative;
}

.skills .card h4{
    padding-top: 30px;
    padding-bottom: 10px;
    font-size: 25px;
    font-weight: 500;
}

.skills .card p{
    line-height: 1.7;
    font-size: 16px;
    color: var(--third-color);
}

.skills .card i{
    font-size: 42px;
    padding: 15px;
    width: 75px;
    height: 75px;
    color: var(--second-color);
    background-color: var(--main-color);
    position: absolute;
    top: calc(-75px / 2);
    transform: rotate(45deg);
    left: 39%;
    transition: 1s;
    border: 1px solid var(--main-color);
}

.skills .card:hover{
    background-color: transparent;
}

.skills .card:hover i{
    transform: rotate(0deg);
    background-color: var(--bg-color);
}

.skills .card:hover h4, .skills .card:hover p{
    color: var(--second-color);
    transition: 1s;
}

.skills a{
    border: 1px solid var(--main-color);
    background-color: var(--main-color);
    border-radius: 2px;
    color: var(--second-color);
    transition: background-color 0.8s;
    padding: 12px 20px;
    letter-spacing: 1.5px;
    z-index: 50px;
    text-decoration: none;
}

.skills a:hover{
    background-color: var(--second-color);
    color: var(--main-color);
}

.support{
  position: relative;
  padding-left: 20px;
  padding-bottom: 20px;
  display: flex;
  background-color: var(--bg-color);
}

.support i{
  color: var(--main-color);
  font-size: 20px;
  margin-left: 8px;
}

.hide1{
  display: none;
  margin-left: 5px;
  margin-right: 10px;
  color: var(--main-color);
  font-size: 15px;
}

.support a:hover + .hide1{
  display: block;
  transition: all 1s;
}
</style> -->


<template>
  <head>
    <title>Card Effect</title>
    </head>
    <body>
      
    
      <div class="container">
        
          <div class="card">
            <div class="face face1">
              <div class="content">
                  <i class="fab fa-windows"></i>            
                <h3>HTML</h3>
              </div>
            </div>
            <div class="face face2">
              <div class="content">
                <H6>Technical Skill</H6>
                <P>HTML</P>
                <div class="progress">
                  <div
                    class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                  >
                    95%
                  </div>
                </div>
              </div>
            </div>
          </div>
        
        <div class="card">
           <div class="face face1">
             <div class="content">
          <i class="fab fa-android"></i>              
           <h3>BOOTSRTAP</h3>
             </div>
           </div>
           <div class="face face2">
             <div class="content">
              <H6>Technical Skill</H6>
              <P>BOOTSRTAP</P>             
                <div class="progress">
                <div
                  class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                >
                  95%
                </div>
              </div>
             </div>
           </div>
        </div>
        
        
        <div class="card">
           <div class="face face1">
             <div class="content">
               <i class="fab fa-apple"></i>
                <h3>MYSQL</h3>
             </div>
           </div>
           <div class="face face2">
             <div class="content">
              <H6>Technical Skill</H6>
              <P>MYSQL</P>
              <div class="progress">
                <div
                  class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                >
                  95%
                </div>
              </div>
             </div>
           </div>
        </div>
        
        
        
        
        <div class="card">
          <div class="face face1">
            <div class="content">
              <i class="fab fa-apple"></i>
               <h3>CSS</h3>
            </div>
          </div>
          <div class="face face2">
            <div class="content">
              <H6>Technical Skill</H6>
              <P>CSS</P>
              <div class="progress">
                <div
                  class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
                >
                  95%
                </div>
              </div>
            </div>
          </div>
       </div>

       <div class="card">
        <div class="face face1">
          <div class="content">
              <i class="fab fa-windows"></i>            
            <h3>Windows</h3>
          </div>
        </div>
        <div class="face face2">
          <div class="content">
            <H6>Technical Skill</H6>
            <P>HTML</P>
            <div class="progress">
              <div
                class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
              >
                95%
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="face face1">
          <div class="content">
              <i class="fab fa-windows"></i>            
            <h3>Windows</h3>
          </div>
        </div>
        <div class="face face2">
          <div class="content">
            <H6>Technical Skill</H6>
            <P>HTML</P>
            <div class="progress">
              <div
                class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
              >
                95%
              </div>
            </div>
          </div>
        </div>
      </div>        

      <div class="card">
        <div class="face face1">
          <div class="content">
              <i class="fab fa-windows"></i>            
            <h3>Windows</h3>
          </div>
        </div>
        <div class="face face2">
          <div class="content">
            <H6>Technical Skill</H6>
            <P>HTML</P>
            <div class="progress">
              <div
                class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
              >
                95%
              </div>
            </div>
          </div>
        </div>
      </div>   

      <div class="card">
        <div class="face face1">
          <div class="content">
              <i class="fab fa-windows"></i>            
            <h3>Windows</h3>
          </div>
        </div>
        <div class="face face2">
          <div class="content">
            <H6>Technical Skill</H6>
            <P>HTML</P>
            <div class="progress">
              <div
                class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
              >
                95%
              </div>
            </div>
          </div>
        </div>
      </div>   

      <div class="card">
        <div class="face face1">
          <div class="content">
              <i class="fab fa-windows"></i>            
            <h3>Windows</h3>
          </div>
        </div>
        <div class="face face2">
          <div class="content">
            <H6>Technical Skill</H6>
            <P>HTML</P>
            <div class="progress">
              <div
                class="progress-bar w-100 progress-bar-striped progress-bar-animated text-end  bg-secondary"
              >
                95%
              </div>
            </div>
          </div>
        </div>
      </div>   
      </div>
      
    </body>
</template>

<script>

</script>

<style scoped>
body{
  display:flex;
  margin:0;
  padding:0;
  min-height: 100vh;

  justify-content: center;
  align-items: center;
  font-family: arial;
}

.container{
  width: 1000px;
  position: relative;
  display: flex;
  justify-content: space-between;
  flex-wrap:wrap;
  
}

.container .card{
  position: relative;
  border:none;
  padding-bottom:70px;
}

.container .card .face{
  width:300px;
  height: 200px;
  transition:.4s;
  
}

.container .card .face.face1{
  position: relative;
  background: #dcabdf;
  display: flex;
  justify-content: center;
  align-content:center;
  align-items: center;
  z-index: 1;
  transform: translateY(100px);
}

.container .card:hover .face.face1{
  transform: translateY(0);
  box-shadow:
    inset 0 0 60px whitesmoke,
    inset 20px 0 80px #f0f,
    inset -20px 0 80px #0ff,
    inset 20px 0 300px #f0f,
    inset -20px 0 300px #0ff,
    0 0 50px #fff,
    -10px 0 80px #f0f,
    10px 0 80px #0ff;
   
}


.container .card .face.face1 .content{
  opacity: .2;
  transition:  0.5s;
  text-align: center;
  
   
  
  
 

}

.container .card:hover .face.face1 .content{
  opacity: 1;
 
}

.container .card .face.face1 .content i{
  font-size: 3em;
  color: black;
  display: inline-block;
   
}

.container .card .face.face1 .content h3{
  font-size: 1em;
  color: white;
  text-align: center;
  

}

.container .card .face.face1 .content a{
   transition: .5s;
}

.container .card .face.face2{
   position: relative;
   background: whitesmoke;
   display: flex;
   align-items: center;
   justify-content: center;
   padding: 20px;
  box-sizing: border-box;
  box-shadow: 0 20px 50px rgba(0,0,0,.8);
  transform: translateY(-100px);
}

.container .card:hover .face.face2{
    transform: translateY(0);


}

.container .card .face.face2 .content p, a{
  font-size: 10pt;
  margin: 0 ;
  padding: 0;
  color:#333;
}

.container .card .face.face2 .content a{
  text-decoration:none;
  color: black;
  box-sizing: border-box;
  outline : 1px dashed #333;
  padding: 10px;
  margin: 15px 0 0;
  display: inline-block;
}

.container .card .face.face2 .content a:hover{
  background: #333 ;
  color: whitesmoke; 
  box-shadow: inset 0px 0px 10px rgba(0,0,0,0.5);
}
</style>

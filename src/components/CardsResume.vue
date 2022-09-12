<template>
  <article
    class="col-md-6 col-lg-4 col-sm-10"
    v-for="item in AboutArray"
    :key="item.id"
  >
    <section class="card-content">
      <div class="card-content">
        <div class="card">
          <div class="layer"></div>
          <div class="content">
            <div class="image">
                <div class="details">
              <!-- <span><span>  <h3> {{item.title}}</h3></span> -->
                <!-- {{ item.text }}</span></br> -->
             <span>{{item.subtext}}</span>
             <br />
           
             </div>
            </div>
            
            
            </div>
          </div>
        </div>
     
    </section>
  </article>
</template>

<script scoped>
export default {
  data() {
    return {
      AboutArray: [
        {
          id: 1,
           title: "Education",
          text: "-Princeton Secondary High School",
          subtext: "text",
         
          
        },
        {
          id: 2,
          title: "Acievements",
          text: "",
          subtext: "text",
          
        
        },
        {
          id: 3, 
          title: "Hobbies",
         text: "",
         subtext: "text",
         
        
        },
        
      ],
    };
  },
};
</script>

<style scoped>
.image {
  width: fit-content;
}
.test h2 {
  font-size: 35px;
  /* color: var(--second-color); */
  padding-bottom: 20px;
}

.test h2 span {
  color: #dcabdf;
}
article{
    overflow-x: hidden;
}

.card-content {
  /* margin: 200px auto 100px; */
   padding-top:20px; 
}

.card-content .card {

  position: relative;
  margin: 0 auto;
  width: 350px;
  background: white;
  color: black;
  /* padding: 20px; */
  box-sizing: border-box;
  
  text-align: center;
  box-shadow: 0 10px 40px  rgba(0, 0, 0, 0.5);
  overflow: hidden;
  border-radius: 30px;
}
.card-content .card .layer {
  position: absolute;
  top: 0;
  left: calc(100% - 2px);
  height: 100%;
  width: 100%;
  background: linear-gradient(#dfb3e2, #dcabdf);
  z-index: 1;
  transition: 0.5s;
}
.card-content .card:hover .layer {
  left: 0;
  right:0;}
.card-content .card .content {
  position: relative;
  z-index: 2;
}
.card-content .card .content p {
  font-size: 18px;
  line-height: 24px;
}
.card-content .card .content .image {
  width: 100%;
  height: 180px;
  /* object-position: -30px 0; */
  /* margin: 0 auto; */

  overflow: hidden;
  border: 5px solid #dcabdf;
  box-shadow: 0 10px 20px  rgba(206, 31, 246, 0.2);
  object-fit: cover;
}
.card-content .card .content .details h2 {
  font-size: 18px;
}
.card-content .card .content .details span {
  color: black;
  font-size: 14px;
  transition: 0.5s;
}
.card-content .card:hover .content .details span {
  color: #fff;
}
.card-content .card:hover .content p {
  color: white;
}

@media all and (max-width: 1250px) {
    .card{
    width: 15em !important;
    }


}
</style>

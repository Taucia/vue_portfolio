<template>
  <article
    class="col-md-6 col-lg-4 col-sm-10"
    v-for="item in AboutArray"
    :key="item.id"
  >
    <div class=" card-content">
      <div class="card-content">
        <div class="card">
          <div class="layer"></div>
          <div class="content">
            <div class="image">
              <img :src="item.icon" alt="avatar" />
            </div>
            <br />
            <div class="details">
              <span>{{ item.title }}</span>
              <div class="col-md">
                <a
                  class="btn btn-primary btn-floating m-1"
                  style="background-color: #333333"
                  :href="item.text"
                  role="button"
                  >Github <i class="fab fa-github"></i></a>
                <a
                  class="btn btn-primary btn-floating m-1"
                  style="background-color:  #dcabdf"
                 :href="item.link"
                  role="button"
                  >Netlify <i class="fa-regular fa-code"></i>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</article>
</template>

<script scoped>
export default {
  data() {
    return {
      AboutArray: [
        {
          id: 1,
          icon: "https://i.postimg.cc/xjyvnLdR/portfoliotask.png",
          title: "Portfolio",
          text: "https://github.com/Taucia/Taucia-jackson-portfolio-project-Final",
          link:"https://app.netlify.com/sites/brilliant-sawine-98dadc/overview",
        },
        {
          id: 2,
          icon: "https://i.postimg.cc/nzxXPwqt/calculator.png",
          title: "Calculator",
          text: "https://github.com/Taucia/calculator.js",
          link:"https://app.netlify.com/sites/resplendent-cendol-019eab/overview",
        },
        {
          id: 3,
          icon: "https://i.postimg.cc/43g4fHy6/Bmi.png",
          title: "BMI Calculator",
          text: "https://github.com/Taucia/Bmi-calculator",
          link:"https://app.netlify.com/sites/phenomenal-gnome-0de544/overview",
        },
        {
          id: 4,
          icon: "https://i.postimg.cc/TwNt9mWg/properties-task.png",
          title: "  Properties Market",
          text: "https://github.com/Taucia/module-task",
          link:"https://app.netlify.com/sites/deft-macaron-047392/overview",
        },
        {
          id: 5,
          icon: "https://i.postimg.cc/SRWDpPv7/to-do-list.png",
          title: "To-do list",
          text: "https://github.com/Taucia/to-do-list-2",
          link:"https://app.netlify.com/sites/fabulous-florentine-1c1b47/overview",
        },
        {
          id: 6,
          icon: "https://i.postimg.cc/mD6GHPL6/blogs.png",
          title: "Food Blog",
          text: "https://github.com/Taucia/blog",
          link:"https://app.netlify.com/sites/starlit-dodol-9f794c/overview",

        },
        {
          id: 7,
          icon: "https://i.postimg.cc/7h0wrx4s/tempcal.png",
          title: "Temperature Clcualtor",
          text: "https://github.com/Taucia/temperature-converter",
          link:"https://app.netlify.com/sites/statuesque-youtiao-80aa9d/overview",
        },
        {
          id: 8,
          icon: "https://i.postimg.cc/yNGHJJYp/simple-compoundcal.png",
          title: "Simple&Compound Interest Calculator",
          text: "https://github.com/Taucia/interest-calculator",
          link:"https://app.netlify.com/sites/kaleidoscopic-moxie-b35cf1/overview",
        },
        {
          id: 9,
          icon: "https://i.postimg.cc/8C78V1BR/areaoftrianglecal.png",
          title: "Area of triangle Calculator",
          text: "https://github.com/Taucia/Area-of-a-triangle",
          link:"https://app.netlify.com/sites/melodic-pie-1d139d/overview",
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

article{
    overflow-x: hidden;
}
.i{
  color:white;
  width:20px;
}
.bi{
  color:white;
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
 
  overflow-x: hidden;
  overflow-y:hidden;
  border-radius: 10px;
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
  box-shadow: 0 10px 20px rgba(206, 31, 246, 0.2);
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

<template>
  <article
    class="col-md-6 col-lg-4 col-sm-12"
    v-for="item in AboutArray"
    :key="item.id"
  >
    <section class="card-content">
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
              <div class="col-4">
                <a
                  class="btn btn-primary btn-floating m-1"
                  style="background-color: #333333"
                  :href="item.text"
                  role="button"
                  ><i class="fab fa-github"></i
                ></a>
                <a
                  class="btn btn-primary btn-floating m-1"
                  style="background-color: #333333"
                  href="https://github.com/Taucia"
                  role="button"
                  ><i class="fab fa-"></i
                ></a>
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
          icon: "https://i.postimg.cc/xjyvnLdR/portfoliotask.png",
          title: "Portfolio",
          text: "https://github.com/Taucia/Taucia-jackson-portfolio-project-Final",
        },
        {
          id: 2,
          icon: "https://i.postimg.cc/nzxXPwqt/calculator.png",
          title: "Calculator",
          text: "https://github.com/Taucia/calculator.js",
        },
        {
          id: 3,
          icon: "https://i.postimg.cc/43g4fHy6/Bmi.png",
          title: "BMI Calculator",
          text: "https://github.com/Taucia/Bmi-calculator",
        },
        {
          id: 4,
          icon: "https://i.postimg.cc/TwNt9mWg/properties-task.png",
          title: "  Properties Market",
          text: "https://github.com/Taucia/module-task",
        },
        {
          id: 5,
          icon: "https://i.postimg.cc/SRWDpPv7/to-do-list.png",
          title: "To-do list",
          text: "https://github.com/Taucia/to-do-list-2",
        },
        {
          id: 6,
          icon: "https://i.postimg.cc/mD6GHPL6/blogs.png",
          title: "Food Blog",
          text: "https://github.com/Taucia/blog",
        },
        {
          id: 7,
          icon: "https://i.postimg.cc/7h0wrx4s/tempcal.png",
          title: "Temperature Clcualtor",
          text: "",
        },
        {
          id: 8,
          icon: "https://i.postimg.cc/yNGHJJYp/simple-compoundcal.png",
          title: "Simple&Compound Interest Calculator",
          text: "",
        },
        {
          id: 9,
          icon: "https://i.postimg.cc/8C78V1BR/areaoftrianglecal.png",
          title: "Area of triangle Calculator",
          text: "",
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
.card-content {
  /* margin: 200px auto 100px; */
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  grid-gap: 20px;
}

.card-content .card {
  position: relative;
  margin: 0 auto;
  width: 350px;
  background: white;
  color: black;
  padding: 20px;
  box-sizing: border-box;
  text-align: center;
  box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5);
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
}
.card-content .card .content {
  position: relative;
  z-index: 2;
}
.card-content .card .content p {
  font-size: 18px;
  line-height: 24px;
}
.card-content .card .content .image {
  width: 200px;
  height: 200px;
  /* object-position: -30px 0; */
  /* margin: 0 auto; */

  overflow: hidden;
  border: 5px solid #dcabdf;
  box-shadow: 0 10px 20px rgba(235, 137, 240, 0.2);
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
</style>

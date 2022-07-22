<template>
  <div class="test">
    <div class="text">
      <h2><span>My </span>Testimonials</h2>
    </div>
  </div>
  <div class="testimonials container">
    <div class="testimonial row">
      <div class="card col-sm-12 c0l-md-4">
        <div class="layer"></div>
        <div class="content">
          <div class="image i">
            <img src="https://i.postimg.cc/qvrdZ3F3/LS2-1.jpg" alt="avatar" />
          </div>
          <br />
          <div class="details">
            <h2>Marshalino Jankowski</h2>
            <h2>Collegue</h2>
            <h2>Swiftyblue11@gmail.com</h2>
            <span
              >Taucia Jackson is someone I would recommend to any company or
              team because she is a team player who is selfless and hardworking.
              She has a keen eye for design and unconventional thinking, which
              is a boon to anyone who is stuck in routine thinking. She has a
              pleasant personality and an approachable demeanor. That, combined
              with her raw talent and unwavering dedication, will undoubtedly
              catapult her into the coding world and establish a name for
              herself and her team in any working environment.</span
            >
          </div>
        </div>
      </div>

      <div class="card col-sm-12 c0l-md-4">
        <div class="layer"></div>
        <div class="content">
          <div class="image i">
            <img src="https://i.postimg.cc/HkvB7Gbk/Emile.jpg" alt="avatar" />
          </div>
          <br />
          <div class="details">
            <h2>Emile van Wyk</h2>
            <h2>Collegue</h2>
            <h2>Emiya.vanwyk@gmail.com</h2>
            <span>Taucia Jackson,  Intuitive, knowledge seeking, always ready to learn new things especially when it comes to her work, she has an eye for detail which when doing the final touches is a must have in any team, all in all she has come a long way since I first met her and she can only go up from here .</span>
          </div>
        </div>
      </div>
      <div class="card col-sm-12 c0l-md-4">
        <div class="layer"></div>
        <div class="content">
          <div class="image i">
            <img
              src="https://i.postimg.cc/L51d6rvJ/monique2.jpg"
              alt="avatar"
            />
          </div>
          <br />
          <div class="details">
            <h2>Monique Dampies</h2>
            <h2>Colleague</h2>
            <h2>Moniquedampies1861@gmail.com</h2>
            <span
              >Taucia's tenacity is one of the many admirable qualities about
              her. She is someone I can proudly call a friend and a colleague.
              Her perspicacity will make her an asset to any to any company. I
              will never have doubts if she is part of my team.</span
            >
          </div>
        </div>
      </div>
      <div class="card col-sm-12 c0l-md-4">
        <div class="layer"></div>
        <div class="content">
          <div class="image i">
            <img src="https://i.postimg.cc/MHGfjmg2/joel2.jpg" alt="avatar" />
          </div>
          <br />
          <div class="details">
            <h2>Joel Mukanya</h2>
            <h2>Lecturer</h2>
            <h2>Joel@lifechoices.co.za</h2>
            <span
              >Taucia, she is a determined, goal-oriented, and self-motivated
              young lady who makessure that her work stands out from
              everyone.</span
            >
          </div>
        </div>
      </div>

      <div class="card col-sm-12 c0l-md-4">
        <div class="layer"></div>
        <div class="content">
          <div class="image i">
            <img src="https://i.postimg.cc/CxSvp1jT/Saleem.jpg" alt="avatar" />
          </div>
          <br />
          <div class="details">
            <h2>Saleem Ariefdien</h2>
            <h2>Colleague</h2>
            <h2>Saleemariefdien@gmail.com</h2>

            <span>
              Taucia is a hardworking individual who is dedicated. Her self
              motivation and perseverance are displayed in her work and she'll
              be a great addition to your company.
            </span>
          </div>
        </div>
      </div>
      <div class="card col-sm-12 c0l-md-4">
        <div class="layer"></div>
        <div class="content">
          <div class="image i">
            <img
              src="https://i.postimg.cc/vmWxwf8w/me3-removebg.png"
              alt="avatar"
            />
          </div>
          <br />
          <div class="details">
            <h2>Shane Stevens</h2>
            <h2>Colleague</h2>
            <h2>ShaneStevensxk9</h2>

            <span
              >Taucia is a self-assured, hardworking, respectable, and quick
              learner. She is a team player who excels on her own, and she has a
              wonderful personality.</span
            >
            <h2></h2>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
body {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: white;
  font-family: sans-serif;
  color: black;
}
.test.text {
  padding-bottom: 20px;
}

.test h2 {
  font-size: 35px;
  /* color: var(--second-color); */
  padding-bottom: 20px;
}

.test h2 span {
  color: #dcabdf;
}

.img {
  height: 50px;
  /* width:0px; */
  object-fit: cover;
}
.testimonial {
  /* margin: 200px auto 100px; */
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  grid-gap: 20px;
}

.testimonial .card {
  position: relative;
  margin: 0 auto;
  width: 90vw;
  margin-left: 2px ;
  background: white;
  color: black;
  padding: 20px;
  box-sizing: border-box;
  text-align: center;
  box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5);
  overflow: hidden;
  border-radius: 30px;
}
.testimonial .card .layer {
  position: absolute;
  top: 0;
  right: calc(100% - 2px);
  height: 100%;
  width: 100%;
  background: linear-gradient(#dfb3e2, #dcabdf);
  z-index: 1;
  transition: 0.5s;
}
.testimonial .card:hover .layer {
  right: 0;
}
.testimonial .card .content {
  position: relative;
  z-index: 2;
}
.testimonial .card .content p {
  font-size: 18px;
  line-height: 24px;
}
.testimonial .card .content .image {
  width: 225px;
  height: 225px;
  margin: 0 auto;
  border-radius: 50%;
  overflow: hidden;
  border: 5px solid #dcabdf;
  box-shadow: 0 10px 20px rgba(235, 137, 240, 0.2);
}
.testimonial .card .content .details h2 {
  font-size: 18px;
}
.testimonial .card .content .details span {
  color: black;
  font-size: 14px;
  transition: 0.5s;
}
.testimonial .card:hover .content .details span {
  color: #fff;
}
.testimonial .card:hover .content p {
  color: white;
}
@media screen and (max-width: 600px) {
  
}
</style>

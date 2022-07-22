<template>

  <div class="ab">
    <div class="text">
      <h2><span>About </span>Me</h2>
    </div>
  </div>
 
   <div class="about">
    <div class="about">
      <div class="card w-100">
        <div class="layer"></div>
        <div class="content">
          <!-- <div class="image i">
            <img src="https://i.postimg.cc/3wZvJFBh/taucia11.png" alt="avatar" />
          </div> -->
          <div class="bg-light text-black align-text-center text-capitalize pt-5 pb-3" id="about-container">
            <img
              id="img"
              src="https://i.postimg.cc/3wZvJFBh/taucia11.png"
              alt="profile picture"
              class="rounded-circle align-items-md-start image "
            />
         <br>


          <div class="details">
            <h2>Taucia Jackson</h2>
            
            <h2>Taucia.Jackson123@gmail.com</h2>
            <span>The Skills I Possess Are Varied, I Am Eager To Learn, I Am
              Assertive And Can Take Initiative, I Follow Instructions Well.I Am
              Hardworking, I Can Work Well With Others And Under-Pressure.I Can
              Work Well As An Individual And In A Team. In Everything I Do, I
              Strive To Do My Best. My Approach To Challenges Is Head On And I
              Have A Hard Time Accepting Failure. As A Person Of Honesty,
              Punctuality, And Sober Habits, I Am Good At Managing My Time.</span>
             
             
       
                    <div class="row">
                      <div class="col-sm-3">
                        <h6 class="mb-0">Full Name</h6>
                      </div>
                      <div class="col-sm-9 text-secondary">Taucia Jackson</div>
                    </div>
                    <hr />
                    <div class="row">
                      <div class="col-sm-3">
                        <h6 class="mb-0">Date of Birth</h6>
                      </div>
                      <div class="col-sm-9 text-secondary">19/03/2000</div>
                    </div>
                    <hr />
                    <div class="row">
                      <div class="col-sm-3">
                        <h6 class="mb-0">Email</h6>
                      </div>
                      <div class="col-sm-9 text-secondary">
                        taucia.jackson123@gmail.com
                      </div>
                    </div>
                    <hr />
                    <div class="row">
                      <div class="col-sm-3">
                        <h6 class="mb-0">Phone</h6>
                      </div>
                      <div class="col-sm-9 text-secondary">084-357-8830</div>
                    </div>
                    <hr />
                    <div class="row">
                      <div class="col-sm-3">
                        <h6 class="mb-0">Address</h6>
                      </div>
                      <div class="col-sm-9 text-secondary">
                        Western Cape, Cape Town, SA
                      </div>
                    </div>
                    <hr />
                    <div class="row">
                      <div class="col-sm-3">
                        <h6 class="mb-0">Github</h6>
                      </div>
                      <div class="col-sm-9 text-secondary">
                        https://github.com/Taucia
                      </div>
                    </div>
                      <hr />
                      <div class="row">
                        <div class="col-sm-3">
                          <h6 class="mb-0">Linkdin</h6>
                        </div>
                        <div class="col-sm-9 text-secondary">
                          https://www.linkedin.com/in/taucia-jackson-a17a29205/
                        </div>
                      </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
 
    
       
     

  
</template>
<script>
export default {};
</script>
<style scoped >
#about-container{
  border-radius: 30px;
}
.ab.text {
  padding-bottom: 20px;
}

.ab h2 {
  font-size: 35px;
  /* color: var(--second-color); */
  padding-bottom: 20px;
}

.ab h2 span {
  color: #dcabdf;
}

container{
  border-radius:15px;
}
/* effect */
.about {
  
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  grid-gap: 20px;
}

.about .card {
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
.about .card .layer {
  position: absolute;
  top: 0;
  right: calc(100% - 2px);
  height: 100%;
  width: 100%;
  background: linear-gradient(#dfb3e2, #dcabdf);
  z-index: 1;
  transition: 0.5s;
}
.about .card:hover .layer {
  right: 0;
}
.about .card .content {
  position: relative;
  z-index: 2;
}
.about .card .content p {
  font-size: 18px;
  line-height: 24px;
}
.about .card .content .image {
  width: 225px;
  height: 225px;
  margin: 0 auto;
  border-radius: 50%;
  overflow: hidden;
  border: 5px solid #dcabdf;
  box-shadow: 0 10px 20px rgba(235, 137, 240, 0.2);
}
.about.card .content .details h2 {
  font-size: 18px;
}
.about.card .content .details span {
  color: black;
  font-size: 14px;
  transition: 0.5s;
}
.about.card:hover .content .details span {
  color: #fff;
}
.about .card:hover .content p {
  color: white;
}
</style>

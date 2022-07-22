<template>
 <div class="con">
    <div class="text">
      <h2><span>Contact </span>Me</h2>
    </div>
  </div>
<div class="contact ">
  <div class=" container text-white size">
    <div class="row">
      <div class="col-md-6 col-sm-12">
        <img src="https://i.postimg.cc/YSdnT1XV/images.jpg" alt="logo" class="img-fluid" />
        
      </div>
      <div class="col-md-4 col-xl-5 col-sm-12">
        <form action="https://formspree.io/f/xknylkka" method="POST">
          <div class="col-md-12">
            <div class="site-heading text-center">
             
            
            </div>
          </div>
          <label for="_name"> Your Name </label>
          <input
            type="text"
            name="_name"
            id="_name"
            placeholder="Name"
            required
          />

          <label for="_replyto"> Your Email </label>
          <input
            type="email"
            name="_replyto"
            id="_replyto"
            placeholder="Email"
            required
          />

          <label for="message"> Message </label>
          <textarea
            name="message"
            id="message"
            placeholder="Leave a Message..."
            required
          ></textarea>

          <button type="submit" class="button">SUBMIT</button>
        </form>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped >
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  background-image: url();
  background-repeat: no-repeat;
  background-size: cover;
}
/* Font: Montserrat 300;400;700
   Color: light blue #d3e2f6
*/
.con .text {
  padding-bottom: 20px;
}

.con h2 {
  font-size: 35px;
  /* color: var(--second-color); */
  padding-bottom: 20px;
}

.con h2 span {
  color: #dcabdf;
}
.social-icons {
  font-size: 3rem;
}
/* .text-primary2 {
  color: aqua;
} */
.size{
  height: 100vh;
}
body {
  font-family: "Montserrat";
  color: #dddddf;
}
form input,
form textarea {
  width: 100%;
  margin: 0.5rem 0;
  padding: 0.5rem;
  border: none;
  outline: none;
  font-family: inherit;
  font-size: 0.9rem;
  background-color: #dfb3e2;
  border-radius: 5px;
  color:white;
 
}
form input:focus,
form textarea:focus {
  border-color: #93b8e99f;
}
textarea {
  min-height: 6rem;
}
form label {
  /* margin-top: 1rem; */
  display: block;
  color: inherit;
  font-weight: 800;
}
form button {
  background-color: #dfb3e2;
  color: rgb(255, 255, 255);
  font-weight: 800;
  letter-spacing: 1px;
  text-transform: uppercase;
  border: none;
  padding: 0.5rem 2rem;
  margin: 0.5rem 0rem;
  border-radius: 10px;
}
form button:hover {
  background-color: #ffffff;
  color:#dfb3e2;
}
.inline {
  display: inline;
  width: initial;
  margin-bottom: 1rem;
}
.text {
  margin-left: 1rem;
}
.site-heading{
margin-bottom: 1rem;
}
.site-heading h2 {
  display: block;
  font-weight: 700;
  text-transform: uppercase;
}
.site-heading h2 span {
  color: #d0c4df;
}
.site-heading h4 {
  display: inline-block;
  /* padding-bottom: 20px; */
  position: relative;
  text-transform: capitalize;
  z-index: 1;
}
.site-heading h4::before {
  /* background: #a00000 none repeat scroll 0 0; */
  bottom: 0;
  content: "";
  height: 2px;
  left: 50%;
  margin-left: -25px;
  position: absolute;
  width: 50px;
}
img{
    height:350px;
    width:350px;
    
}
</style>
<template>
<nav class="navbar navbar-expand-lg bg-light ">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">

  
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <router-link to="/" class="nav-link active">
            <i class="bi bi-house-heart"></i>Home
          </router-link>

          <!-- <a class="nav-link active" aria-current="page" href="#">Home</a> -->
        </li>
        <li class="nav-item">
          <router-link to="/about" class="nav-link active">
          About
          </router-link>
          {{images.u}}
          <!-- <a class="nav-link" href="#">About</a> -->
        </li>
        <li class="nav-item">
    <router-link to="/resume" class="nav-link active">
            Resume
          </router-link>
        </li>
        <li class="nav-item">
    <router-link to="/Projects" class="nav-link active">
            Projects
          </router-link>
        </li>
         <li class="nav-item">
    <router-link to="/Skills" class="nav-link active">
            Skills
          </router-link>
        </li>
        <li class="nav-item">
    <router-link to="/Testamonials" class="nav-link active">
            Testamonials
          </router-link>
        </li>
        <li class="nav-item">
           <router-link to="/contact" class="nav-link active">
            Contact
          </router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  data(){
    return {
      images:[
        {
          u:''
        }
      ]
    }
  }
};
</script>

<style scoped>
</style>

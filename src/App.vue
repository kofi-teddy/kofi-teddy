<template>
  <div class="mt-0 bg-main">
    <div id="nav">
      <div>
        <div>
          <div class="flex items-center justify-center flex-auto">
            <div class="w-full max-w-sm p-10 bg-green-900 rounded-3xl rounded-t-none">
              <div class="mt-1 text-sm text-gray-50 text-center">
                <span class="mx-1"><router-link to="/">Home</router-link></span>
                <span class="mx-1"><router-link to="/blog">Blog</router-link></span>
                <span class="mx-1"><router-link to="/projects">Projects</router-link></span>
                <span class="mx-1"><router-link to="/contact">Contact</router-link></span>
              </div>     
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <router-view/>

   <!-- Footer -->
    <div class="pt-8 mt-20">
      <div class="mt-5">
        <div class="flex items-center justify-center flex-auto">
          <div class="w-full max-w-sm p-10 text-center">
            <div class="text-gray-100 text-md">
              Teddy M. Agudogo
            </div>
            <div class="mt-2 text-sm text-gray-100">
              <a href="mailto:agudogot@gmail.com" target="_blank">agudogot@gmail.com</a>
            </div>
            <div class="mt-1 text-gray-100 text-xm">
              <a href="tel:+2330208556743" target="_blank">+233 20 855 6743</a>
            </div>
            <div class="mt-1 text-xs text-gray-100">
              <span class="mx-1"><a href="https://www.linkedin.com/in/teddy-agud/" target="_blank">Linkedin</a></span>
              <span class="mx-1"><a href="https://twitter.com/kofi_teddy_" target="_blank">Twitter</a></span>
              <span class="mx-1"><a href="https://github.com/kofi-teddy" target="_blank">Github</a></span>
              <span class="mx-1"><a href="https://stackoverflow.com/users/16498815/kofi-teddy" target="_blank">Stackoverflow</a></span>
            </div>
            <div class="mt-1 text-xs text-gray-100">
              copyright © 2021
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>


  export default {
    // data() {
    //   return { 
    //     pictureHoverEffect: "https://pbs.twimg.com/profile_images/1445269368980574221/pjRaoz6b_400x400.jpg",
    //     pictureStatic: "https://media-exp1.licdn.com/dms/image/C4E03AQFbTzcJ6iEPMA/profile-displayphoto-shrink_400_400/0/1597954295899?e=1642032000&v=beta&t=GQvK2IgWAaj5HwauQ9-mI7W3O0y4OGwR8bNmcQ9cAns",
    //     hover: false
    //   }
    // },
    // computed: {
    //   pictureHover () {
    //     if (this.hover == true) {
    //       return this.pictureHoverEffect
    //     } else {
    //       return this.pictureStatic
    //     }
    //   }
    // }
  }
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=PT+Serif&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap');

  .kt-font-title{
    font-family: 'PT Serif',serif;
  }
  body {
    font-family: 'Inter';
    background: #0000;
  }

  .btn {
    @apply py-2 px-4 font-semibold rounded-xl shadow-md rounded-full px-4 py-2 text-sm;
  }
  .container{
    @apply p-20;
    font-family: 'Inter';
  }
  
  .btn-green {
    @apply text-white bg-green-500 hover:bg-green-700;
  }

  .bg-main {
    background: #000;
  }
  
</style>

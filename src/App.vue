<template>
  <div class="container bg-main">
    <!-- <div class="grid grid-cols-3 gap-1 pt-6">
      <div class="text-center">
        <img 
          :src="pictureHover"
          @mouseover="hover = true" 
          @mouseleave="hover = false"  
          class="border-4 border-green-400 shadow-xl w-44 h-44 rounded-3xl" 
          alt="">
      </div>

      <div>
        <h2 class="mt-2 font-serif text-4xl font-extrabold leading-8 tracking-tight text-gray-100 sm:text-3xl kt-font-title">Hi, I'm</h2>
        <h1 class="mt-3 text-4xl font-extrabold leading-8 tracking-tight text-gray-100 sm:text-4xl kt-font-title">
          <span class="font-serif text-green-600 kt-font-title">
            Teddy M. Agudogo
          </span>  
        </h1>
        <h2 class="mt-2 font-bold leading-8 tracking-tight text-gray-300 text-md sm:text-2xl">Software Engineer</h2>
        <div class="py-1 mt-16">
          <a href="#!" class="px-1 py-2.5 bg-green-500 rounded-xl text-xs text-white btn shadow-xl">
            <span class="px-3">
              Download CV 
            </span>
            <span class="ml-2 p-1.5 bg-green-300 rounded-lg">&#8594;</span>
          </a>
        </div>
      </div>
      
      <div>
        <div class="mb-4">
          <span class="text-sm text-green-600">My profile</span>
        </div>
        <div>
          <span class="mt-2 text-2xl font-extrabold tracking-tight text-gray-300">
            Based in Ghana <br> I'm a full stack developer
          </span>
        </div>
        <div class="mt-6">
          <span class="max-w-2xl mt-4 text-gray-300 text-md lg:mx-auto">
            A hardworking individual and a good team player with the ability to build shared vision with demonstrated ability in fast-paced learning. Possessing critical thinking skills while being goal-oriented and a good communicator fuels my good adaptability skills.
          </span>
        </div>
        <div class="mt-4">
          <a class="text-sm text-green-600" href="#!">
            +233 0 55 923 094 4
          </a>
        </div>
        <div class="mt-1">
          <a class="text-sm text-green-600" href="#!">
            agudogot@gmail.com
          </a>
        </div>
      </div>
    </div> -->

    <div class="pt-8 mt-20">
      <div class="mt-5">
        <div class="flex items-center justify-center flex-auto">
          <div class="w-full max-w-sm p-10 text-center">            
            <div class="text-center">
              <div class="text-center">
                <img 
                :src="pictureHover"
                @mouseover="hover = true" 
                @mouseleave="hover = false"  
                class="w-40 h-40 mx-auto text-center border-4 border-green-400 shadow-xl rounded-3xl" 
                alt="">
              </div>
              <div class="mt-8 font-extrabold leading-8 tracking-tight text-gray-100">
                <h1 class="font-serif text-3xl font-extrabold leading-8 tracking-tight text-gray-100">
                  Teddy M. Agudogo
                </h1>
                <h3 class="mt-2 text-xl font-extrabold leading-8 tracking-tight text-gray-100">Software Engineer</h3>
              </div>
              <div class="mt-8">
                <a 
                  href="https://res.cloudinary.com/kofi-teddy/image/upload/v1629886095/pdf/teddys-cv-2021_3_vkvyti.pdf" 
                  class="px-1 py-2.5 bg-green-500 rounded-xl text-xs text-white btn shadow-xl"
                  target="_blank">
                  <span class="px-3">
                    Download CV 
                  </span>
                  <span class="ml-2 p-1.5 bg-green-300 rounded-lg">&#8594;</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="pt-8 mt-20">
      <div class="text-center">
        <h1 class="mt-2 font-serif text-4xl font-extrabold leading-8 tracking-tight text-gray-100 sm:text-4xl kt-font-title">Bio</h1>
      </div>
      <div class="mt-5">
        <div class="flex items-center justify-center flex-auto">
          <div class="w-full max-w-sm p-10 border-4 border-green-400 rounded-3xl">

            <div class="text-white">
              <p class="p-0 m-0 text-sm"> 
                I'm a software engineer based in Ghana. Very passionate about building robust data driven application. 
                I mostly do fullstack development but I really love backend development with almost a decade experience.
              </p>
              <p class="p-0 m-0 mt-2 text-sm"> 
                I'm Cofounder of Skycrew Technologies, a software development consulting company based in Ghana. 
                At Skycrew Technologies I enjoy mentoring interns, sharing my experience with them.  
              </p>
            </div>

          </div>
        </div>
      </div>
    </div>


    <div class="pt-8 mt-20 text-center">
      <h1 class="mt-2 font-serif text-4xl font-extrabold leading-8 tracking-tight text-gray-100 sm:text-4xl kt-font-title">Tools & Proficiency</h1>
      <div class="mt-5">
        <div class="flex items-center justify-center flex-auto">
          <div class="w-full max-w-sm p-10 border-4 border-green-400 rounded-3xl">

            <div class="relative pt-1">
              <div class="flex items-center justify-between mb-2">
                <div>
                  <span class="inline-block px-2 py-1 text-xs font-semibold text-yellow-400 uppercase bg-blue-500 rounded-full">
                    Python
                  </span>
                </div>
                <div class="text-right">
                  <span class="inline-block text-xs font-semibold text-yellow-400">
                    90%
                  </span>
                </div>
              </div>
              <div class="flex h-2 mb-4 overflow-hidden text-xs bg-yellow-400 rounded">
                <div style="width:90%" class="flex flex-col justify-center text-center text-white bg-blue-500 shadow-none whitespace-nowrap"></div>
              </div>
            </div>

            <div class="relative pt-1">
              <div class="flex items-center justify-between mb-2">
                <div>
                  <span class="inline-block px-2 py-1 text-xs font-semibold text-green-600 uppercase bg-green-200 rounded-full">
                    Django
                  </span>
                </div>
                <div class="text-right">
                  <span class="inline-block text-xs font-semibold text-green-700">
                    94%
                  </span>
                </div>
              </div>
              <div class="flex h-2 mb-4 overflow-hidden text-xs bg-green-200 rounded">
                <div style="width:94%" class="flex flex-col justify-center text-center text-white bg-green-700 shadow-none whitespace-nowrap"></div>
              </div>
            </div>

            <div class="relative pt-1">
              <div class="flex items-center justify-between mb-2">
                <div>
                  <span class="inline-block px-2 py-1 text-xs font-semibold text-red-600 uppercase bg-red-200 rounded-full">
                    Wagtail
                  </span>
                </div>
                <div class="text-right">
                  <span class="inline-block text-xs font-semibold text-red-600">
                    95%
                  </span>
                </div>
              </div>
              <div class="flex h-2 mb-4 overflow-hidden text-xs bg-red-200 rounded">
                <div style="width:95%" class="flex flex-col justify-center text-center text-white bg-red-500 shadow-none whitespace-nowrap"></div>
              </div>
            </div>

            <!-- <div class="relative pt-1">
              <div class="flex items-center justify-between mb-2">
                <div>
                  <span class="inline-block px-2 py-1 text-xs font-semibold text-green-600 uppercase bg-green-200 rounded-full">
                    Vue
                  </span>
                </div>
                <div class="text-right">
                  <span class="inline-block text-xs font-semibold text-green-600">
                    75%
                  </span>
                </div>
              </div>
              <div class="flex h-2 mb-4 overflow-hidden text-xs bg-green-200 rounded">
                <div style="width:65%" class="flex flex-col justify-center text-center text-white bg-green-500 shadow-none whitespace-nowrap"></div>
              </div>
            </div> -->

          </div>
        </div>
      </div>
      <!-- <div class="mt-5">
        <h3 class="mt-2 font-bold leading-8 tracking-tight text-gray-300 text-md sm:text-2xl">Python, Django, FastAPI, Vuejs, AWS, GCP, Tailwindcss, Bootstrap, Wagtail</h3>
      </div> -->
    </div>

    <div class="pt-8 mt-20 text-center">
      <h1 class="mt-2 font-serif text-4xl font-extrabold leading-8 tracking-tight text-gray-100 sm:text-4xl kt-font-title">Skills & Competence</h1>
      <div class="mt-5">
        <div class="flex items-center justify-center flex-auto">
          <div class="w-full max-w-sm p-10 border-4 border-green-400 rounded-3xl">

            <div class="text-white">
              <span>Web App  Development - 95%</span>
            </div>

            <div class="text-white">
              <span>API Design - 90%</span>
            </div>

            <div class="text-white">
              <span>Deployment - 80%</span>
            </div>

            <div class="text-white">
              <span>Data modeling - 88%</span>
            </div>

          </div>
        </div>
      </div>
      <!-- <div class="mt-5">
        <h3 class="mt-2 font-bold leading-8 tracking-tight text-gray-300 text-md sm:text-2xl">Python, Django, FastAPI, Vuejs, AWS, GCP, Tailwindcss, Bootstrap, Wagtail</h3>
      </div> -->
    </div>

    <div class="pt-8 mt-20">
      <div class="text-center">
        <h1 class="mt-2 font-serif text-4xl font-extrabold leading-8 tracking-tight text-gray-100 sm:text-4xl kt-font-title">Experience</h1>
      </div>
      <div class="mt-5">
        <div class="flex items-center justify-center flex-auto">
          <div class="w-full max-w-sm p-10 border-4 border-green-400 rounded-3xl">

            <div class="text-white">
              <span> - Skycrew Technologies</span>
              <p class="p-0 m-0 text-xs"><b>CTO & Software Engineer</b>, 2019 - Present</p>
            </div>

            <div class="mt-4 text-white">
              <span> - Thai Union Group,PCL</span>
              <p class="p-0 m-0 text-xs"><b>IT & Software Maintenance</b>, 2016 - 2019</p>
            </div>

            <div class="mt-4 text-white">
              <span> - Ghana Port And Harbour Authority</span>
              <p class="p-0 m-0 text-xs"><b>MIS</b>, 2016 - 2017</p>
            </div>

          </div>
        </div>
      </div>
      <!-- <div class="mt-5">
        <h3 class="mt-2 font-bold leading-8 tracking-tight text-gray-300 text-md sm:text-2xl">Python, Django, FastAPI, Vuejs, AWS, GCP, Tailwindcss, Bootstrap, Wagtail</h3>
      </div> -->
    </div>

    <div class="pt-8 mt-20">
      <div class="text-center">
        <h1 class="mt-2 font-serif text-4xl font-extrabold leading-8 tracking-tight text-gray-100 sm:text-4xl kt-font-title">Achievement & Projects</h1>
      </div>
      <div class="mt-5">
        <div class="flex items-center justify-center flex-auto">
          <div class="w-full max-w-sm p-10 border-4 border-green-400 rounded-3xl">

            <div class="text-white">
              <span> - Nelmma Courier</span>
              <p class="p-0 m-0 text-xs">Track & Trace App</p>
            </div>

            <div class="mt-4 text-white">
              <span> - Osabarimba Awards</span>
              <p class="p-0 m-0 text-xs">Nominations & Voting App</p>
            </div>

            <div class="mt-4 text-white">
              <span> - IntelAfrique</span>
              <p class="p-0 m-0 text-xs">Data Analysis Driven App</p>
            </div>

          </div>
        </div>
      </div>
      <!-- <div class="mt-5">
        <h3 class="mt-2 font-bold leading-8 tracking-tight text-gray-300 text-md sm:text-2xl">Python, Django, FastAPI, Vuejs, AWS, GCP, Tailwindcss, Bootstrap, Wagtail</h3>
      </div> -->
    </div>

    <div class="pt-8 mt-20">
      <div class="text-center">
        <h1 class="mt-2 font-serif text-4xl font-extrabold leading-8 tracking-tight text-gray-100 sm:text-4xl kt-font-title">Education</h1>
      </div>
      <div class="mt-5">
        <div class="flex items-center justify-center flex-auto">
          <div class="w-full max-w-sm p-10 border-4 border-green-400 rounded-3xl">

            <div class="text-white">
              <span> - University of Ghana, Legon</span>
              <p class="p-0 m-0 text-xs"><b>Degree BSc. I.T.</b>, 2013 - 2017</p>
            </div>

            <div class="mt-4 text-white">
              <span> - St. Augustine’s College</span>
              <p class="p-0 m-0 text-xs"><b>Business</b>, 2009 - 2013</p>
            </div>

          </div>
        </div>
      </div>
      <!-- <div class="mt-5">
        <h3 class="mt-2 font-bold leading-8 tracking-tight text-gray-300 text-md sm:text-2xl">Python, Django, FastAPI, Vuejs, AWS, GCP, Tailwindcss, Bootstrap, Wagtail</h3>
      </div> -->
    </div>

    <div class="pt-8 mt-20">
      <div class="text-center">
        <h1 class="mt-2 font-serif text-4xl font-extrabold leading-8 tracking-tight text-gray-100 sm:text-4xl kt-font-title">Awards & Certifications</h1>
      </div>
      <div class="mt-5">
        <div class="flex items-center justify-center flex-auto">
          <div class="w-full max-w-sm p-10 border-4 border-green-400 rounded-3xl">

            <div class="text-white">
              <span> - IBM Certified Mobile Application Developer, </span>
              <span class="p-0 m-0 text-xs"><b> Issued</b>, 2016</span>
            </div>

            <div class="mt-4 text-white">
              <span> - IBM Certified Application Security Specialist, </span>
              <span class="p-0 m-0 text-xs"><b> Issued</b>, 2016</span>
            </div>

          </div>
        </div>
      </div>
    </div>

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
              <a href="tel:+2330208556743" target="_blank">+233 0 20 855 674 3</a>
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

  <!-- <footer class="px-4 py-12 text-sm leading-5 border-t border-gray-200 bg-gray-50 md:py-14 sm:px-6 lg:px-16">
    <div class="mx-auto space-y-6 text-center max-w-10xl md:space-y-0 md:text-left md:flex">
      <div class="flex flex-col items-center space-y-6 md:space-y-0 md:space-x-10 md:flex-row">
        <div class="flex items-center space-x-2">
          <div class="relative overflow-hidden rounded-full">
            <img src="./assets/img/my-profile-pics.jpeg" alt="" class="bg-gray-200" style="width:30px;height:30px" loading="lazy">
            <div class="absolute inset-0 border border-black rounded-full border-opacity-10"></div>
          </div>
          <p>Developed by 
            <a href="#!" class="font-medium text-gray-900 transition-colors duration-150 hover:text-gray-500">@kofi_teddy_</a>
          </p>
        </div>
      </div>
      <a href="#!" class="inline-flex items-center space-x-2 text-[#1da1f2] ml-auto font-medium mr-2">
        <svg width="20" height="20" fill="currentColor"><path d="M6.29 18.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0020 3.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.073 4.073 0 01.8 7.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 010 16.407a11.616 11.616 0 006.29 1.84"></path></svg>
      </a>
      <a href="#!" class="inline-flex items-center space-x-2 text-[#1da1f2] font-medium mr-2">
        <svg width="24" height="24" viewBox="0 0 16 16" fill="currentColor"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
      </a>
    </div>
  </footer> -->

</template>

<script>


  export default {
    data() {
      return { 
        pictureHoverEffect: "https://pbs.twimg.com/profile_images/1445269368980574221/pjRaoz6b_400x400.jpg",
        pictureStatic: "https://media-exp1.licdn.com/dms/image/C4E03AQFbTzcJ6iEPMA/profile-displayphoto-shrink_400_400/0/1597954295899?e=1642032000&v=beta&t=GQvK2IgWAaj5HwauQ9-mI7W3O0y4OGwR8bNmcQ9cAns",
        hover: false
      }
    },
    computed: {
    pictureHover () {
      if (this.hover == true) {
        return this.pictureHoverEffect
      } else {
        return this.pictureStatic
      }
    }
  }
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
    background: #1f2424;
  }
  
</style>

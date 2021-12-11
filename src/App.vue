<template>
  <div class="container bg-main">
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
                  href="https://res.cloudinary.com/kofi-teddy/image/upload/v1639263328/pdf/teddys-cv-2021_2_abseyt.pdf" 
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
                I really love and enjoy backend development.
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
          </div>
        </div>
      </div>
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

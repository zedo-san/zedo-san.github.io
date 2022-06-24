<script setup></script>

<template>
  <div class="container 2xl:px-96 pt-8 mx-auto h-screen w-full">
    <div class="flex flex-col w-full pb-8">
      <section>
        <h1 class="text-4xl leading-6 font-bold text-gray-900 pb-4">Zedfeld G. Busiños</h1>
        <h2 class="text-2xl leading-3 pb-4">Frontend Developer</h2>
      </section>
      <div class="divider"></div>
      <section class="pt-4">
        <h3 class="text-2xl font-bold leading-3 text-gray-800 pb-2">Stack</h3>
        <p class="pb-4">Driven to add more skills in the near future.</p>
        <ul class="flex gap-1 flex-wrap">
          <li class="badge badge-secondary rounded-md p-4">HTML</li>
          <li class="badge badge-secondary rounded-md p-4">CSS</li>
          <li class="badge badge-secondary rounded-md p-4">SCSS/SASS</li>
          <li class="badge badge-secondary rounded-md p-4">Javascript</li>
          <li class="badge badge-secondary rounded-md p-4">Typescript</li>
          <li class="badge badge-secondary rounded-md p-4">Vue.js</li>
          <li class="badge badge-secondary rounded-md p-4">Vuex</li>
          <li class="badge badge-secondary rounded-md p-4">Nuxt.js</li>
          <li class="badge badge-secondary rounded-md p-4">React.js</li>
          <li class="badge badge-secondary rounded-md p-4">Redux</li>
          <li class="badge badge-secondary rounded-md p-4">Framer Motion</li>
          <li class="badge badge-secondary rounded-md p-4">styled-components</li>
          <li class="badge badge-secondary rounded-md p-4">Tailwind CSS</li>
          <li class="badge badge-secondary rounded-md p-4">Vuetify</li>
          <li class="badge badge-secondary rounded-md p-4">Node.js</li>
          <li class="badge badge-secondary rounded-md p-4">Express.js</li>
        </ul>
      </section>
      <div class="divider"></div>
      <section>
        <h3 class="text-2xl font-bold leading-3 text-gray-800 pb-2">Projects</h3>
        <p class="pb-4">
          I have here a few of the projects that I built. More are in progress and will be deployed soon.
        </p>
        <ul class="list-disc pt-4 px-5">
          <li>
            <span class="text-xl font-bold inline-block mb-2">Dynamic Freelancer -
              <a
                class="badge badge-outline rounded-full"
                href="https://www.dynamicfreelancer.ae/"
                target="_blank"
                rel="noreferrer"
              >
                https://www.dynamicfreelancer.ae/
                </a>
            </span>
            <p class="mb-4"> Made with 
              <span class="badge badge-secondary rounded-full">Nuxt.js</span>
              and
              <span class="badge badge-secondary rounded-full">Vuetify</span>
              .
            </p>
            <figure>
                <img src="./assets/images/dynamic-freelancer.png" class="rounded-lg shadow-lg" />
              </figure>
          </li>
          <div class="divider py-8"></div>
          <li>
            <span class="text-xl font-bold inline-block mb-2">FreelancerVisa -
              <a
                class="badge badge-outline rounded-full"
                href="https://www.freelancervisa.com/"
                target="_blank"
                rel="noreferrer"
              >
                https://www.freelancervisa.com/
                </a>
            </span>
            <p class="mb-4"> Made with 
              <span class="badge badge-secondary rounded-full">Nuxt.js</span>
              and
              <span class="badge badge-secondary rounded-full">Vuetify</span>
              .
            </p>
            <figure>
                <img src="./assets/images/freelancer-visa.png" class="rounded-lg shadow-lg" />
              </figure>
          </li>
        </ul>
      </section>
    </div>
    <footer class="footer footer-center p-4 bg-base-300 text-base-content">
      <div>
        <p>Copyright © 2022 - All right reserved by Zedfeld G. Busiños </p>
      </div>
    </footer>
  </div>
</template>

<style></style>

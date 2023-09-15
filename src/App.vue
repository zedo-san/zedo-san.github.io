<script setup>
import { computed } from "vue"

const yearToday = computed(() => {
  return new Date().getFullYear()
})
</script>

<template>
  <div class="container 2xl:px-96 pt-8 mx-auto h-screen w-full px-4">
    <div class="flex flex-col w-full pb-8">
      <section>
        <h1 class="text-4xl leading-6 font-bold text-gray-900 pb-4">Zedfeld G. Busiños</h1>
        <h2 class="text-2xl leading-3 pb-4">Frontend Developer</h2>
      </section>
      <section>
        <div>✉️ <a href="mailto:zedfeld.businos@gmail.com">zedfeld.businos@gmail.com</a></div>
      </section>
      <div class="divider"></div>
      <section>
        <p>
          👋 Hello, I'm Zedfeld Busiños, a passionate and experienced software developer with a track record of turning
          ideas into efficient, user-friendly, and innovative digital solutions. With almost 4 years of hands-on
          experience in the tech industry, I'm here to bring your digital dreams to life.
        </p>
        <br />
        <p>
          I'm not just a software developer; I'm your partner in turning your ideas into reality. Whether you're a
          startup looking to build an MVP, a business aiming to streamline operations, or an individual with a unique
          project in mind, I'm here to help.
        </p>
        <br />
        <p>
          Let's have a conversation about your project, your goals, and how we can work together to make it a resounding
          success. Feel free to get in touch and let's bring your digital vision to life!
        </p>
      </section>
      <div class="divider"></div>
      <section class="pt-4">
        <h3 class="text-2xl font-bold leading-3 text-gray-800 pb-2">Skills</h3>
        <p class="pb-4">Driven to add more of them in the future.</p>
        <ul class="flex gap-1 flex-wrap">
          <li class="badge badge-secondary rounded-md p-4">Vue</li>
          <li class="badge badge-secondary rounded-md p-4">Vuex</li>
          <li class="badge badge-secondary rounded-md p-4">Vuetify</li>
          <li class="badge badge-secondary rounded-md p-4">Nuxt</li>
          <li class="badge badge-secondary rounded-md p-4">React</li>
          <li class="badge badge-secondary rounded-md p-4">Next.js</li>
          <li class="badge badge-secondary rounded-md p-4">Redux</li>
          <li class="badge badge-secondary rounded-md p-4">Tanstack Query / React Query</li>
          <li class="badge badge-secondary rounded-md p-4">Typescript</li>
          <li class="badge badge-secondary rounded-md p-4">Javascript</li>
          <li class="badge badge-secondary rounded-md p-4">Tailwind CSS</li>
          <li class="badge badge-secondary rounded-md p-4">Bootstrap</li>
          <li class="badge badge-secondary rounded-md p-4">Framer Motion</li>
          <li class="badge badge-secondary rounded-md p-4">Figma</li>
          <li class="badge badge-secondary rounded-md p-4">styled-components</li>
          <li class="badge badge-secondary rounded-md p-4">Node.js</li>
          <li class="badge badge-secondary rounded-md p-4">Express.js</li>
          <li class="badge badge-secondary rounded-md p-4">SCSS/SASS</li>
          <li class="badge badge-secondary rounded-md p-4">HTML</li>
          <li class="badge badge-secondary rounded-md p-4">CSS</li>
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
            <span class="text-xl font-bold inline-block mb-2"
              >Prosperna -
              <a
                class="badge badge-outline rounded-full"
                href="https://www.prosperna.com/"
                target="_blank"
                rel="noreferrer"
              >
                https://prosperna.com/
              </a>
            </span>
            <div class="mb-4 flex flex-wrap items-center gap-1">
              <span>Made with</span>
              <span class="flex gap-1 items-center">
                <span class="badge badge-secondary rounded-full">React</span>,
                <span class="badge badge-secondary rounded-full">Tanstack Query / React Query</span>,
                <span class="badge badge-secondary rounded-full">Next.js</span>,
              </span>
              <span>and</span>
              <span class="badge badge-secondary rounded-full">Bootstrap</span>
              .
            </div>
            <figure>
              <img src="./assets/images/prosperna.png" class="rounded-lg shadow-lg" />
            </figure>
          </li>
          <div class="divider py-8"></div>
          <li>
            <span class="text-xl font-bold inline-block mb-2"
              >Dynamic Freelancer -
              <a
                class="badge badge-outline rounded-full"
                href="https://www.dynamicfreelancer.ae/"
                target="_blank"
                rel="noreferrer"
              >
                https://www.dynamicfreelancer.ae/
              </a>
            </span>
            <p class="mb-4">
              Made with
              <span class="badge badge-secondary rounded-full">Nuxt.js</span>
              and
              <span class="badge badge-secondary rounded-full">Vuetify</span>
              .
            </p>
            <figure><img src="./assets/images/dynamic-freelancer.png" class="rounded-lg shadow-lg" /></figure>
          </li>
          <div class="divider py-8"></div>
          <li>
            <span class="text-xl font-bold inline-block mb-2"
              >FreelancerVisa -
              <a
                class="badge badge-outline rounded-full"
                href="https://www.freelancervisa.com/"
                target="_blank"
                rel="noreferrer"
              >
                https://www.freelancervisa.com/
              </a>
            </span>
            <p class="mb-4">
              Made with
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
        <p>Copyright © {{yearToday}} - All right reserved by Zedfeld G. Busiños</p>
      </div>
    </footer>
  </div>
</template>

<style></style>

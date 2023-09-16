<script setup>
import { computed } from "vue";
import Heading3 from "./components/Heading/Heading3.vue";
import RedirectBadge from "./components/RedirectBadge/RedirectBadge.vue";

const yearToday = computed(() => {
  return new Date().getFullYear();
});

const yearsOfExperience = computed(() => {
  return yearToday.value - new Date("2019-08-10").getFullYear();
});
</script>

<template>
  <div class="container 2xl:px-96 pt-8 mx-auto h-screen w-full px-4">
    <div class="flex flex-col w-full pb-8">
      <section class="mb-3">
        <h1 class="text-2xl text-center 2xl:text-left md:text-4xl leading-6 font-bold text-gray-900 pb-4">
          Zedfeld G. Busiños
        </h1>
        <h2 class="text-lg text-center 2xl:text-left md:text-2xl leading-3 pb-4">Frontend Developer</h2>
      </section>
      <section>
        <div class="text-center 2xl:text-left">
          ✉️ <a href="mailto:zedfeld.businos@gmail.com">zedfeld.businos@gmail.com</a>
        </div>
      </section>
      <div class="divider"></div>
      <section class="text-justify">
        <p>
          👋 Hello, I'm Zedfeld Busiños, a passionate and experienced software developer with a track record
          of turning ideas into efficient, user-friendly, and innovative digital solutions. With almost
          {{ yearsOfExperience }} years of hands-on experience in the tech industry, I'm here to bring your
          digital dreams to life.
        </p>
        <br />
        <p>
          I'm not just a software developer; I'm your partner in turning your ideas into reality. Whether
          you're a startup looking to build an MVP, a business aiming to streamline operations, or an
          individual with a unique project in mind, I'm here to help.
        </p>
        <br />
        <p>
          Let's have a conversation about your project, your goals, and how we can work together to make it a
          resounding success. Feel free to get in touch and let's bring your digital vision to life!
        </p>
      </section>
      <div class="divider"></div>
      <section class="pt-4">
        <Heading3>Skills</Heading3>
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
        <Heading3>Projects</Heading3>
        <p class="pb-4">
          These projects represent my dedication to crafting solutions that bridge innovation and
          functionality. I invite you to explore this showcase of my work, each project is a testament to the
          passion and skill I bring to software development. If you're interested in collaborating or have a
          project in mind, feel free to reach out and let's discuss how I can help turn your ideas into
          reality.
        </p>
        <ul class="list-disc pt-4 px-5">
          <li>
            <span class="text-xl font-bold inline-block mb-2"
              >Prosperna -
              <RedirectBadge redirectLink="https://prosperna.com" />
            </span>
            <p class="mb-4">
              Prosperna is the leading E-Commerce software platform in the Philippines that helps micro, small
              and medium-sized businesses launch their online store, sell everywhere, accept payments and
              automatically book shipping and stay ahead of the curve.
            </p>
            <div class="mb-4 flex items-center flex-wrap gap-1">
              <span>Made with</span>
              <span class="badge badge-secondary rounded-full">React</span>,
              <span class="badge badge-secondary rounded-full">Tanstack Query / React Query</span>,
              <span class="badge badge-secondary rounded-full">Next.js</span>,
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
              <RedirectBadge redirectLink="https://www.dynamicfreelancer.ae/" />
            </span>
            <p class="mb-4">
              Providing the most comprehensive platform for freelancers to freelance legally in the UAE with
              over 120+ freelance activities. A 2-year onshore employment visa issued under the Ministry of
              human resources, immigration and labor making your freelance journey 100% legal and hassle-free.
            </p>
            <div class="mb-4 flex items-center flex-wrap gap-1">
              <span> Made with </span>
              <span class="badge badge-secondary rounded-full">Nuxt.js</span>
              <span> and </span>
              <span class="badge badge-secondary rounded-full">Vuetify</span>
              .
            </div>
            <figure><img src="./assets/images/dynamic-freelancer.png" class="rounded-lg shadow-lg" /></figure>
          </li>
          <div class="divider py-8"></div>
          <li>
            <span class="text-xl font-bold inline-block mb-2"
              >FreelancerVisa -
              <RedirectBadge redirectLink="https://www.freelancervisa.com/" />
            </span>
            <p class="mb-2">
              FreelancerVisa.com is the leading On shore freelancing platform in the UAE. Licensed by the
              Ministry of Labor and offer the most comprehensive platform for Individuals looking to legally
              freelance in the UAE.
            </p>
            <p class="mb-4">
              Freelancers under this platform can take up temporary or contract jobs, part-time jobs and
              project based work in the UAE mainland and Freezones.
            </p>
            <div class="mb-4 flex flex-wrap gap-1">
              <span> Made with </span>
              <span class="badge badge-secondary rounded-full">Nuxt.js</span>
              <span> and </span>
              <span class="badge badge-secondary rounded-full">Vuetify</span>
              .
            </div>
            <figure>
              <img src="./assets/images/freelancer-visa.png" class="rounded-lg shadow-lg" />
            </figure>
          </li>
        </ul>
      </section>
    </div>
    <footer class="footer footer-center p-4 bg-base-300 text-base-content">
      <div>
        <p>Copyright © {{ yearToday }} - All right reserved by Zedfeld G. Busiños</p>
      </div>
    </footer>
  </div>
</template>

<style></style>

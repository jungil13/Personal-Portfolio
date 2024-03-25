<template>
  <div id="apps" class="home flex flex-col md:flex-row items-center justify-center bg-slate-700">
    <!-- Content Section -->
    <div class="content text-center md:text-left md:mr-8">
      <div class="intro">
        <h1 id="typed" class="text-2xl md:text-4xl font-extrabold leading-tight tracking-tight mb-4 text-yellow-500">Hi, I'm Jun Gil Casquejo </h1>
        <p class="mb-2 text-lg text-white py-4 font-bold leading-tight tracking-tight">Welcome to my digital space where creativity meets innovation</p>
        <p class="mb-4 text-lg text-white font-bold leading-tight tracking-tight"> As a passionate BSIT student at Cordova Public College</p>
        <p class="mb-4 text-lg text-white font-bold">I strive to merge technical expertise to craft captivating digital experiences.</p>
      </div>
      <div class="flex flex-wrap justify-center md:justify-start"> <!-- Button Container -->
      <router-link to="/projects" class="btn btn-primary">Get Started</router-link>
    <a href="https://web.facebook.com/jungil.casquejo30" class="btn btn-facebook"><i class="fa-brands fa-facebook-f"></i>Facebook</a>
    <a href="https://twitter.com" class="btn btn-twitter"><i class="fa-brands fa-twitter"></i>Twitter</a>
    <a href="https://www.instagram.com" class="btn btn-instagram"><i class="fa-brands fa-instagram"></i>Instagram</a>
      </div>
    </div> 
    <!-- Image Section -->
    <div class="character max-w-xs md:max-w-md">
      <img src="/images/ako.png" alt="Ako" class="w-full h-auto">
    </div>
    <router-view></router-view>
  </div>

  <section id="body" class="bg-white dark:bg-gray-900 antialiased">
  <div class="max-w-screen-xl px-4 py-8 mx-auto lg:px-6 sm:py-16 lg:py-24">
    <div class="max-w-2xl mx-auto text-center">
      <h2 class="text-3xl font-extrabold leading-tight tracking-tight text-yellow-400 sm:text-4xl dark:text-white ">
        My Specialties
      </h2>
      <p class="mt-4 text-base font-normal text-gray-400 sm:text-xl dark:text-gray-400">
        Crafted with skill and care to help our clients grow their business!
      </p>
    </div>

    <div class="grid grid-cols-1 mt-12 text-center sm:mt-16 gap-x-20 gap-y-12 sm:grid-cols-2 lg:grid-cols-3">
      <div class="space-y-4">
        <span
          class="bg-gray-100 text-gray-900 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-gray-300">
          Alphabet Inc.
        </span>
        <h3 class="text-2xl font-bold leading-tight text-yellow-300 dark:text-white">
          Web Developer
        </h3>
        <p class="text-lg font-normal text-gray-500 dark:text-gray-400">
          A web developer in IT is a professional who specializes in creating applications or websites that are accessible via the internet. 
        </p>
        <a href="#" title=""
          class="text-white bg-primary-700 justify-center hover:bg-primary-800 inline-flex items-center  focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
          role="button">
          View case study
          <svg aria-hidden="true" class="w-5 h-5 ml-2 -mr-1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"
            fill="currentColor">
            <path fill-rule="evenodd"
              d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
              clip-rule="evenodd" />
          </svg>
        </a>
      </div>

      <div class="space-y-4">
        <span
          class="bg-gray-100 text-gray-900 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-gray-300">
          Trainings.
        </span>
        <h3 class="text-2xl font-bold leading-tight text-yellow-300 dark:text-white">
          Computer System Servicing
        </h3>
        <p class="text-lg font-normal text-gray-500 dark:text-gray-400">
          computer system servicing is essential for maintaining the reliability, security, and performance of IT infrastructure within an organization.
        </p>
        <a href="#" title=""
          class="text-white bg-primary-700 justify-center hover:bg-primary-800 inline-flex items-center  focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
          role="button">
          View case study
          <svg aria-hidden="true" class="w-5 h-5 ml-2 -mr-1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"
            fill="currentColor">
            <path fill-rule="evenodd"
              d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
              clip-rule="evenodd" />
          </svg>
        </a>
      </div>

      <div class="space-y-4">
        <span
          class="bg-gray-100 text-gray-900 text-xs font-medium inline-flex items-center px-2.5 py-0.5 rounded dark:bg-gray-700 dark:text-gray-300">
          Adobe Inc.
        </span>
        <h3 class="text-2xl font-bold leading-tight text-yellow-300 dark:text-white">
          Hardware Technician
        </h3>
        <p class="text-lg font-normal text-gray-500 dark:text-gray-400">
          A hardware technician in IT is a professional who specializes in the installation, maintenance, and repair of computer hardware components and systems.
        </p>
        <a href="#" title=""
          class="text-white bg-primary-700 justify-center hover:bg-primary-800 inline-flex items-center  focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
          role="button">
          View case study
          <svg aria-hidden="true" class="w-5 h-5 ml-2 -mr-1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"
            fill="currentColor">
            <path fill-rule="evenodd"
              d="M12.293 5.293a1 1 0 011.414 0l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-2.293-2.293a1 1 0 010-1.414z"
              clip-rule="evenodd" />
          </svg>
        </a>
      </div>
    </div>
  </div>
</section>
</template>

<script>
import Typed from 'typed.js'; // Importing Typed.js library

export default {
  mounted() {
    // Initialize Typed.js
    const options = {
      strings: ['Hi!! this is Jun Gil Casquejo', 'A BSIT student at Cordova Public College', 'Competent and hardworking'],
      typeSpeed: 50, // Typing speed in milliseconds
      loop: true // Loop the typing animation
    };

    const typed = new Typed('#typed', options);
  },
  methods: {
    handleGetStarted() {
      // Handle the click event of the "Get Started" button
      // Add your logic here
    }
  }
};
</script>

<style>
#apps{
  background-color: #141818;
}
#body{
  background-color: #232b2b;
}#foot{
  background-color: #353839;
}

/* No need to define styles here since Tailwind CSS is used */
.btn {
  padding: 0.5rem 1rem;
  margin: 0.5rem;
  font-size: 1rem;
  border-radius: 0.375rem;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

.btn-primary {
  background-color: teal;
  color: white;
}

.btn-primary:hover {
  background-color: #008080;
}

.btn-facebook {
  background-color: #3b5998;
  color: white;
}

.btn-twitter {
  background-color: #1da1f2;
  color: white;
}

.btn-instagram {
  background-color: #c13584;
  color: white;
}
</style>

<template>
  <div id="app">
    <nav class="flex items-center justify-between flex-wrap bg-gray-900 p-6">
      <div class="flex items-center flex-shrink-0 text-white mr-6">
        <img
          src="/images/logo.png"
          alt=""
          class="fill-current h-10 w-20 mr-2"
          width="54"
          height="54"
          viewBox="0 0 54 54"
        />
        <span class="font-semibold text-xl tracking-tight"></span>
        <!-- Add your brand name here -->
      </div>
      <button
        @click="toggleNavbar"
        type="button"
        class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
        aria-controls="navbar-default"
        :aria-expanded="isNavbarOpen.toString()"
      >
        <span class="sr-only">Open main menu</span>
        <svg
          class="w-5 h-5"
          aria-hidden="true"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 17 14"
        >
          <path
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M1 1h15M1 7h15M1 13h15"
          />
        </svg>
      </button>
      <div
        class="w-full block flex-grow lg:flex lg:items-center lg:w-auto justify-center"
        :class="{ hidden: !isNavbarOpen }"
      >
        <!-- Toggle visibility based on isNavbarOpen -->
        <div class="text-sm lg:flex-grow">
          <div class="text-center">
            <!-- Container to center the links -->
            <router-link
              class="block mt-4 lg:inline-block lg:mt-0 text-white  hover:bg-yellow-600 px-4 py-2 rounded-md mr-5 font-sans font-bold"
              :to="{ path: '/' }"
              active-class="active-link"
            >
              Home
            </router-link>
            <router-link
              class="block mt-4 lg:inline-block lg:mt-0 text-white  hover:bg-yellow-600 px-4 py-2 rounded-md mr-5 font-bold"
              :to="{ path: '/projects' }"
              active-class="active-link"
            >
              Projects
            </router-link>
            <router-link
              class="block mt-4 lg:inline-block lg:mt-0 text-white  hover:bg-yellow-600 px-4 py-2 rounded-md mr-5 font-bold"
              :to="{ path: '/contact' }"
              active-class="active-link"
            >
              Contact
            </router-link>
            <router-link
              class="block mt-4 lg:inline-block lg:mt-0 text-white  hover:bg-yellow-600 px-4 py-2 rounded-md mr-5 font-bold"
              :to="{ path: '/about' }"
              active-class="active-link"
            >
              About
            </router-link>
          </div>
        </div>
        <div class="text-center">
          <a
            href="#"
            class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-teal-500 hover:bg-white mt-4 lg:mt-0"
            >Get Started</a
          >
        </div>
      </div>
    </nav>
    <router-view></router-view>
  </div>
  <footer id="foot" class="text-white rounded-lg shadow py-6 text-center">
        <span class="block text-sm text-white sm:text-center dark:text-gray-400">© 2024 <a href="https://flowbite.com/" class="hover:underline">Portfolio™</a>. All Rights Reserved [JUN GIL].</span>
</footer>
</template>

<script>
export default {
  data() {
    return {
      isNavbarOpen: false,
    };
  },
  methods: {
    toggleNavbar() {
      this.isNavbarOpen = !this.isNavbarOpen;
    },
  },
};
</script>

<style scoped>
.active-link {
  border-bottom: 2px solid white;
}
</style>

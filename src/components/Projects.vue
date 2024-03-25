<!-- Projects.vue -->
<template>
  <section class="py-8 px-4" id="project">
    <h2 class="text-2xl md:text-4xl font-extrabold leading-tight tracking-tight mb-4 text-center text-yellow-400">Some of my Recent Projects</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 lg:gap-8">
      <!-- Card component repeated six times -->
      <div v-for="(project, index) in projects" :key="index" class="overflow-hidden bg-black rounded-lg shadow-lg mx-auto">
        <img :src="project.image" :alt="project.title" class="w-full h-40 md:h-48 object-cover object-center">
        <div class="p-4 md:p-6 bg-black ">
          <h3 class="font-semibold text-lg md:text-xl mb-2 text-yellow-400 cursor-pointer">{{ project.title }}</h3>
          <p class="text-gray-100 text-sm md:text-base cursor-pointer">{{ project.description }}</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      projects: [
        {
          title: "Time Wise - LARAVEL",
          description: "A blogging website about time management  and productivity. it has many features like calendar integration and todo app for scheduling tasks",
          image: "/images/timewise.png",
        },
        {
          title: "Account Manager",
          description: "Account manager is a system that manage the users account like updating users password and assigning roles.",
          image: "/images/account.png",
        },
        {
          title: "Real Time Chat by LARAVEL",
          description: "Real time chat is a chat system offer by laravel through library",
          image: "/images/realchat.png",
        },
        {
          title: "Music Player - SPOTIFY API",
          description: "A music player using spotify api and fetch api in javascript.",
          image: "/images/spotify.png",
        },
        {
          title: "Ecommerce Website - LARAVEL",
          description: "Clothing Ecommerce created with laravel",
          image: "/images/ecom.png",
        },
        {
          title: "Portfolio - Vue",
          description: "My personal portfolio using vue js framework and tailwind css",
          image: "/images/port.png",
        },
      ],
    };
  },
};
</script>

<style scoped>
#project{
  background-color: #141818;
}
/* Add your custom styles here */
</style>

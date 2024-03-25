<template>
  <div class="flex flex-col items-center min-h-screen">
    <div class="text-center">
      <div class="mx-auto mb-4 mt-20 md:mt-32 h-48 w-48 md:h-64 md:w-64 overflow-hidden rounded-full bg-gradient-to-tr from-orange-500 to-purple-700">
        <img src="/images/jungil.png" alt="" class="w-full h-full object-cover" />
      </div>
      <h1 class="max-w-screen-sm text-4xl font-extrabold text-white mb-8">
        I do code and <br />
        computer <span class="text-transparent bg-clip-text bg-gradient-to-tr from-orange-500 to-purple-700">software and hardware installation!</span>
      </h1>
      <p class="mx-auto mb-16 text-lg font-light text-gray-400 max-w-lg">I am a student at Cordova Public College, taking the bachelor of computer science
        major in programming, I am not a pro coder but i am doing my best to  learn as much as possible about coding and to survive college.
      </p>
      <div class="text-center">
        <button class="text-gray-800 inline-block px-8 py-4 mr-4 bg-white rounded-full font-semibold text-lg">Get In Touch</button>
        <button class="text-white inline-block px-8 py-4 bg-transparent border-2 border-white rounded-full font-semibold text-lg">Download CV</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // Component logic
};
</script>

<style scoped>
@media (min-width: 640px) {
  .h-24 {
    height: 6rem; /* Adjust the height for smaller screens */
  }
  .w-24 {
    width: 6rem; /* Adjust the width for smaller screens */
  }
}
</style>

<template>
    <div class="relative h-screen overflow-hidden">
      <!-- Background Video -->
      <video
        autoplay
        muted
        loop
        class="absolute inset-0 object-cover w-full h-full z-0"
      >
        <source src="../assets/vid2.mp4" type="video/mp4" />
        Your browser does not support the video tag.
      </video>
  
      <!-- Overlay Content -->
      <div
        class="relative z-10 flex flex-col items-center justify-center h-full text-white bg-black bg-opacity-40 px-4 sm:px-6 lg:px-8"
      >
        <div class="text-center">
          <h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold">Unleash innovation</h1>
          <p class="text-xl sm:text-2xl mt-4">Easy Deployment with Holsan</p>
          <button
            class="mt-6 px-6 py-3 bg-black text-white rounded-lg hover:bg-gray-800"
          >
            Learn More
          </button>
        </div>
      </div>
  
      <!-- Optional arrows or next buttons -->
      <div
        class="absolute right-4 bottom-4 text-white text-2xl cursor-pointer z-10"
      >
        <span>&#8250;</span>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "HeroSection",
  };
  </script>
  
  <style scoped>
  /* Optional custom styles if needed */
  </style>
  
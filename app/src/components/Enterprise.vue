<template>
    <!-- Main Section Background -->
    <div class="bg-gray-900 text-white p-6 lg:p-12 min-h-screen">
      <!-- ENTERPRISE Title (Center-Aligned) -->
      <div class="text-center mb-12">
        <h1 class="text-6xl sm:text-7xl md:text-8xl font-bold tracking-wider text-gray-100">
          ENTERPRISE
        </h1>
      </div>
  
      <!-- Content Section with Text on Left and First Image on Right -->
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 lg:gap-12 items-start">
        <!-- Left Side: Text Content -->
        <div>
          <h2 class="text-3xl sm:text-4xl font-semibold leading-tight mb-4">
            Comprehensive Enterprise Drone Solutions
          </h2>
          <p class="text-base sm:text-lg mb-4">
            We are a team of drone experts dedicated to developing and supporting
            comprehensive UAV solutions and fleets for organizations across a
            multitude of industry verticals. Established in 2014, we helped
            hundreds of enterprises find and implement the best UAV solution for
            their unique operational needs.
          </p>
          <button
            class="bg-white text-black font-semibold py-3 px-6 rounded-md hover:bg-gray-300"
          >
            Talk to an Expert
          </button>
        </div>
  
        <!-- Right Side: First Image -->
        <div class="lg:order-1">
          <img
            src="https://www.dronenerds.com/cdn/shop/files/Rectangle_52.jpg?v=1688992951&width=500"
            class="object-cover w-full h-80 rounded-lg"
            alt="Enterprise Drone"
          />
        </div>
      </div>
  
      <!-- Second Image with Text Beside It -->
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 lg:gap-12 items-start mt-12">
        <!-- Left Side: Second Image -->
        <div>
          <img
            src="https://www.dronenerds.com/cdn/shop/files/Rectangle_51.jpg?v=1688992927&width=800"
            class="object-cover w-full h-64 rounded-lg"
            alt="Enterprise Drone Image 2"
          />
        </div>
  
        <!-- Right Side: Text Content Beside Second Image -->
        <div>
          <p class="text-base sm:text-lg">
            Our team of drone experts are dedicated to developing and supporting
            enterprise drone programs for organizations across a multitude of
            industry verticals. <br /><br />
            For more information, visit our Enterprise website and learn why Drone Nerds will elevate your operations.
          </p>
          <br />
          <button
            class="bg-white text-black font-semibold py-3 px-6 rounded-md hover:bg-gray-300"
          >
            Visit Drone Nerds Enterprise
          </button>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: "EnterpriseSection",
  };
  </script>
  
  <style scoped>
  /* Optional custom styles if needed */
  </style>
  
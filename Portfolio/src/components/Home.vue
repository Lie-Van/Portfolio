<template>
    <div class="home flex flex-col md:flex-row items-center justify-center bg-white">
      
      <div class="content text-center md:text-left md:mr-8">
        <div class="intro">
      <h1 id="typed" class="text-4xl font-extrabold leading-tight tracking-tight mb-8 text-black-500">
        <span class="rgb-animation text-4xl">Hello, I'm Jonerie</span>
      </h1>
      <p class="mb-2 text-xl text-black font-semibold leading-tight tracking-tight">
       
      </p>
      <p class="mb-6 text-xl text-black font-semibold leading-tight tracking-tight">
       
      </p>
    </div>
        
      </div> 
      
      <div class="character max-w-xs md:max-w-md">
        <img src="/images/profile.jpg" alt="Ako" class="w-full h-auto rounded-full">
      </div>
      <router-view></router-view>
    </div>
  
    <section class="container mx-auto py-8 mb-6">
    <h1 class="text-3xl font-bold mb-6 text-center leading-tight tracking-tight text-red-800">My Projects</h1>
    <h1 class="text-2xl font-semibold mb-6 text-center font-sans text-gray-800">Some of my Recent Projects</h1>
     <
      <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
        <img class="w-full h-40 object-cover" src="/images/ecom.png" alt="Project Image">
        <div class="p-4">
          <h2 class="text-lg font-semibold mb-2">Ecommerce Website</h2>
          <p class="text-gray-700 mb-4">Description of Project 2. Ecommerce website for clothing.</p>
          <button class="text-red-800 text-lg font-semibold">View More</button>
        </div>
      </div>
      
      
      <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
        <img class="w-full h-40 object-cover" src="/images/spotify.png" alt="Project Image">
        <div class="p-4">
          <h2 class="text-lg font-semibold mb-2">Spotify API</h2>
          <p class="text-gray-700 mb-4">Description of Project 3. Spotify Api made with Node Js</p>
          <button class="text-red-800 text-lg font-semibold">View More</button>
        </div>
      </div>
      
      <!-- Card 4 -->
      <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
        <img class="w-full h-40 object-cover" src="/images/timewise.png" alt="Project Image">
        <div class="p-4">
          <h2 class="text-lg font-semibold mb-2">TimeWise - Laravel</h2>
          <p class="text-gray-700 mb-4">App Dev Project - it is a blogging website for time management</p>
          <button class="text-red-800 text-lg font-semibold">View More</button>
        </div>
      </div>
      
      <!-- Card 5 -->
      <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
        <img class="w-full h-40 object-cover" src="/images/account.png" alt="Project Image">
        <div class="p-4">
          <h2 class="text-lg font-semibold mb-2">Account Manager</h2>
          <p class="text-gray-700 mb-4">Description of Project 5. A system for managing accounts like add user roles and changing password</p>
          <button class="text-red-800 text-lg font-semibold">View More</button>
        </div>
      </div>
      
      <!-- Card 6 -->
      <div class="bg-white rounded-lg overflow-hidden shadow-md hover:shadow-lg border border-red-600">
        <img class="w-full h-40 object-cover" src="/images/port.png" alt="Project Image">
        <div class="p-4">
          <h2 class="text-lg font-semibold mb-2">Portfolio Website</h2>
          <p class="text-gray-700 mb-4">Description of Project 6. My personal Portfolio made with vue js frontend only</p>
          <button class="text-red-800 text-lg font-semibold">View More</button>
        </div>
      </div>

    
  </section>
  
  <section class="container mx-auto py-8">
    
      
      
  </section>
  
  
  
  </template>
  
  <script>
  </script>
  
  <style scoped>
  .rgb-animation {
    animation: rgbAnimation 3s infinite alternate;
  }
  
  @keyframes rgbAnimation {
    0% {
      color: rgb(15, 13, 13);
    }
    33% {
      color: rgb(8, 8, 8);
    }
    66% {
      color: rgb(1, 1, 8);
    }
    100% {
      color: rgb(2, 2, 2);
    }
  }
  </style>
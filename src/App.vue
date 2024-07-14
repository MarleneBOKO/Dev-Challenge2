<script setup>
</script>

<template>
  <div class="flex items-center justify-center min-h-screen bg-[#F2F5F9] p-4"> 
    <div class="relative flex flex-col gap-3 bg-white rounded-lg shadow-lg w-full max-w-lg md:w-[440px]">
      <!-- Image principale -->
      <img src="../public/images/hero-image-business-card.png" alt="" class="rounded-lg h-48 w-full object-cover md:h-72">
     
      <!-- SVG pour la forme en vague -->
      <div class="absolute top-40  md:top-64 left-0 w-full overflow-hidden rounded-t-md">
        <svg class="block w-full h-10 md:h-10 transform scale-x-[-1]" viewBox="0 0 1440 320" preserveAspectRatio="none">
          <path fill="#FFFFFF" d="M0,96L48,85.3C96,75,192,53,288,42.7C384,32,480,32,576,58.7C672,85,768,139,864,149.3C960,160,1056,128,1152,122.7C1248,117,1344,139,1392,149.3L1440,160V320H1392C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320H0Z"></path>
        </svg>
      </div>

      <!-- Contenu -->
      <div class="flex flex-col p-4 gap-3">
        <h2 class="text-[#111729] text-[20px] md:text-[24px] font-light font-poppins">Perfect solution for small <br> business</h2>
        <p class="text-[#677489] text-[14px] md:text-[16px] font-lato">Small businesses need to generate leads to grow. <br>
           You can use tools like Ringy.</p>
      </div>
      <hr class="text-[#4b4d50]">
      <div class="flex flex-row gap-3 p-4">
        <div class="bg-[#F2F5F9] rounded-full flex justify-center items-center w-10 h-10">
          <img src="../public/images/avatar-image-business-card.png" alt="" class="rounded-full w-8 h-8">
        </div>
        <div class="flex flex-col gap-0">
          <span class="text-[#111729] text-[12px] md:text-[16px] font-bold font-lato">Amy Burgess</span>
          <span class="text-[#677489] text-[10px] md:text-[12px] font-lato">Customer Manager, Solution Oy</span>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@400;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap');

.font-lato {
  font-family: 'Lato', sans-serif;
}

.font-poppins {
  font-family: 'Poppins', sans-serif;
}

body {
  font-family: 'Lato', sans-serif;
}
</style>

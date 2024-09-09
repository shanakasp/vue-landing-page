<template>
  <div class="relative w-full h-screen flex items-center p-4">
    <!-- Text Content -->
    <div
      class="relative z-10 w-full flex flex-col gap-5 text-center md:text-left text-container"
    >
      <!-- First Row: Title -->
      <div
        class="text-[#091133] text-2xl md:text-4xl font-medium font-['Roboto'] leading-tight md:leading-[66px] tracking-wide"
      >
        Introduce Your Product Quickly & Effectively
      </div>
      <!-- Second Row: Description -->
      <div
        class="text-[#505f98] text-base md:text-lg font-normal font-['Roboto'] leading-relaxed pt-4 md:pt-8"
      >
        Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo
        ligula eget dolor. Aenean<br />massa. Cum sociis natoque penatibus et
        magnis dis parturient montes, nascetur ridiculus <br />mus. <br /><br />
        Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem.
        <br />
        Nulla consequat massa quis enim.
      </div>
      <!-- Third Row: Button Container -->
      <div class="flex flex-col md:flex-row gap-4 mt-4 md:mt-8">
        <!-- First Button -->
        <button
          class="w-full md:w-[189.13px] h-9 bg-[#111b47] text-white text-base font-medium font-['Roboto'] leading-relaxed rounded-sm"
        >
          Purchase UI Kit
        </button>
        <!-- Second Button -->
        <button
          class="w-full md:w-[189.13px] h-9 border-2 border-[#091133] text-[#091133] text-base font-medium font-['Roboto'] leading-relaxed rounded-sm"
        >
          Learn More
        </button>
      </div>
      <!-- Fourth Row: Additional Content (Optional) -->

      <!-- Fifth Row: Footer or Other Elements (Optional) -->
    </div>

    <!-- Image as Background -->
    <div
      class="absolute top-[-10%] right-0 w-[75%] h-[80%] bg-no-repeat bg-cover bg-right bg-transparent"
      :style="{ backgroundImage: `url(${require('../assets/bodyimage.png')})` }"
    ></div>
  </div>
</template>

<script>
export default {
  name: "BodyOne",
};
</script>

<style scoped>
.bg-right {
  background-position: right top;
  background-size: contain;
  height: 100%;
}

/* New class for text container padding */
.text-container {
  padding-left: 10%;
  padding-right: 0; /* Adjust if needed */
}

/* For responsive design on smaller screens */
@media (max-width: 768px) {
  .relative {
    flex-direction: column;
    justify-content: center;
  }

  .bg-right {
    background-position: bottom center;
    background-size: cover;
    opacity: 0.7;
    z-index: 0;
  }

  .z-10 {
    z-index: 1;
  }

  .text-container {
    padding-left: 5%;
    padding-right: 5%;
  }
}
</style>

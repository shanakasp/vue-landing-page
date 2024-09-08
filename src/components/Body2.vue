<template>
  <div class="relative w-full h-screen overflow-hidden p-10">
    <div class="flex flex-col md:flex-row w-full h-full">
      <!-- Left Container -->
      <div
        class="w-full md:w-1/2 p-4 md:p-8 lg:p-20 flex flex-col justify-between relative z-10"
      >
        <div class="flex flex-col justify-center items-start gap-4">
          <div
            class="text-[#091133] text-2xl md:text-3xl lg:text-4xl font-medium font-['Roboto'] leading-tight md:leading-[40px] lg:leading-[48px]"
          >
            Light, Fast & Powerful
          </div>
          <div
            class="text-[#6f7cb2] text-sm md:text-base lg:text-lg font-normal font-['Roboto'] leading-relaxed"
          >
            Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean
            commodo ligula eget dolor. Aenean massa. Cum sociis natoque
            penatibus et magnis dis parturient montes, nascetur ridiculus mus.
            Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem.
            Nulla consequat massa quis enim.
          </div>
          <br />
          <div
            class="p-4 bg-white bg-opacity-80 rounded-md w-full sm:w-[255px] relative"
          >
            <div class="absolute top-2 flex justify-center items-center">
              <img class="w-9 h-9" src="../assets/Icon.png" alt="Icon" />
            </div>
            <div class="flex flex-col items-start mt-12">
              <div
                class="text-[#091133] text-base font-medium font-['Roboto'] leading-relaxed mb-2"
              >
                Title Goes Here
              </div>
              <div
                class="text-[#5d6970] text-xs font-normal font-['Roboto'] leading-[18px]"
              >
                Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean
                commodo ligula eget dolor.
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Right Container -->

      <!-- Right Container (Desktop and Larger Screens) -->
      <div class="hidden md:block absolute top-10 right-0 p-20">
        <img
          src="../assets/image2.png"
          alt="Right Image"
          class="w-auto h-auto max-w-full max-h-full"
        />
      </div>

      <!-- Right Container (Small Screens) -->
      <div class="block md:hidden w-full absolute bottom-0 left-0 p-10">
        <img
          src="../assets/image2.png"
          alt="Right Image"
          class="w-full h-auto max-w-full object-contain"
        />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "BodyTwo",
};
</script>

<style scoped>
/* Add any additional styles here if needed */
</style>

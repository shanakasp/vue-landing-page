<template>
  <div
    class="relative w-full h-screen max-w-screen-lg mx-auto p-4 flex flex-col md:flex-row items-center"
  >
    <!-- Text Content -->
    <div
      class="relative z-10 w-full md:w-1/2 flex flex-col justify-center items-start gap-5 md:pr-8"
    >
      <div
        class="text-[#091133] text-2xl md:text-4xl font-medium font-['Roboto'] leading-tight md:leading-[66px] tracking-wide w-full"
      >
        Introduce Your Product Quickly & Effectively
      </div>
      <div
        class="text-[#505f98] text-base md:text-lg font-normal font-['Roboto'] leading-relaxed w-full pt-4 md:pt-8"
      >
        Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo
        ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis
        dis parturient montes, nascetur ridiculus
        <br />mus. Donec quam felis, ultricies nec, pellentesque eu, pretium
        quis, sem. Nulla consequat massa quis enim.
      </div>
      <div class="flex flex-col md:flex-row gap-4 mt-4 md:mt-8">
        <button
          class="w-full md:w-[189.13px] h-9 bg-[#111b47] text-white text-base font-medium font-['Roboto'] leading-relaxed rounded-sm"
        >
          Purchase UI Kit
        </button>
        <button
          class="w-full md:w-[189.13px] h-9 border-2 border-[#091133] text-[#091133] text-base font-medium font-['Roboto'] leading-relaxed rounded-sm"
        >
          Learn More
        </button>
      </div>
    </div>

    <!-- Image -->
    <div class="relative w-full md:w-1/2 h-full overflow-hidden">
      <img
        src="../assets/bodyimage.png"
        alt="Product Image"
        class="w-full h-full object-cover"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "BodyOne",
};
</script>

<style scoped>
/* Add any additional styles here if needed */
</style>

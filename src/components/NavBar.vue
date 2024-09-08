<template>
  <nav class="bg-transparent shadow-md relative z-10">
    <div class="max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between items-center h-16">
        <!-- Left side: Navigation links -->
        <div class="flex space-x-8">
          <a
            href="#"
            class="text-sm font-normal text-[#505f98] font-['Roboto']"
          >
            Home
          </a>
          <a
            href="#"
            class="text-sm font-normal text-[#505f98] font-['Roboto']"
          >
            About
          </a>
          <a
            href="#"
            class="text-sm font-normal text-[#505f98] font-['Roboto']"
          >
            Contact
          </a>
        </div>
        <!-- Right side: Buy Now button -->
        <div class="hidden md:block">
          <button
            class="bg-[#111b47] text-white font-medium text-xs py-2 px-8 rounded-sm"
          >
            Buy Now
          </button>
        </div>
        <!-- Mobile menu button -->
        <div class="-mr-2 flex md:hidden">
          <button
            @click="isOpen = !isOpen"
            class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-white hover:bg-gray-700 focus:outline-none focus:bg-gray-700 focus:text-white"
          >
            <svg
              class="h-6 w-6"
              stroke="currentColor"
              fill="none"
              viewBox="0 0 24 24"
            >
              <path
                v-if="isOpen"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M6 18L18 6M6 6l12 12"
              />
              <path
                v-else
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M4 6h16M4 12h16M4 18h16"
              />
            </svg>
          </button>
        </div>
      </div>
    </div>

    <!-- Mobile Menu -->
    <div v-if="isOpen" class="md:hidden bg-transparent">
      <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
        <a
          href="#"
          class="block text-sm font-normal text-[#505f98] font-['Roboto']"
        >
          Home
        </a>
        <a
          href="#"
          class="block text-sm font-normal text-[#505f98] font-['Roboto']"
        >
          About
        </a>
        <a
          href="#"
          class="block text-sm font-normal text-[#505f98] font-['Roboto']"
        >
          Contact
        </a>
        <button
          class="w-full bg-[#111b47] text-white font-medium text-xs py-2 mt-2 rounded-sm"
        >
          Buy Now
        </button>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      isOpen: false, // Toggle for mobile menu
    };
  },
};
</script>

<style scoped>
/* Add any additional styles if needed */
</style>

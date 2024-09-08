<template>
  <footer
    class="relative w-full bg-cover bg-center py-16 md:py-20 lg:py-24"
    :style="{
      backgroundImage: `url(${require('@/assets/Back.png')})`,
      backgroundPosition: 'center center',
      backgroundSize: 'cover',
      backgroundAttachment: 'fixed',
    }"
  >
    <div class="max-w-screen-xl mx-auto px-6 sm:px-8 md:px-12 lg:px-16">
      <div class="text-center mb-12 md:mb-16 lg:mb-20">
        <!-- First Row: Title -->
        <div
          class="Title w-full max-w-[600px] mx-auto text-[#091133] text-2xl sm:text-3xl md:text-4xl lg:text-5xl font-medium font-['Roboto'] leading-tight md:leading-[48px] lg:leading-[56px] mb-8 md:mb-10 lg:mb-12"
        >
          A Price To Suit Everyone
        </div>

        <!-- Second Row: Body Text -->
        <div
          class="Body w-full max-w-[600px] mx-auto text-[#6f7cb2] text-sm sm:text-base md:text-lg lg:text-xl font-normal font-['Roboto'] leading-relaxed mb-8 md:mb-10 lg:mb-12"
        >
          Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean
          commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus
          et magnis dis parturient montes, nascetur ridiculus mus.
        </div>

        <!-- Third Row: Price -->
        <div
          class="Price w-full max-w-[350px] mx-auto text-[#222f65] text-3xl sm:text-4xl md:text-[50px] lg:text-[60px] font-medium font-['Roboto'] leading-tight md:leading-[66px] tracking-wide mb-8 md:mb-1 lg:mb-1 pt-7"
        >
          $40
        </div>

        <!-- Fourth Row: UI Design Kit Title -->
        <div
          class="Title w-full max-w-[350px] mx-auto text-[#37447e] text-base sm:text-lg md:text-base lg:text-lg font-normal font-['Roboto'] leading-relaxed mb-8 md:mb-10 lg:mb-12"
        >
          UI Design Kit
        </div>

        <!-- Fifth Row: Body Text -->
        <div
          class="Body w-full max-w-[350px] mx-auto text-[#5d6970] text-sm sm:text-base md:text-sm lg:text-base font-normal font-['Roboto'] leading-normal mb-8 md:mb-1 lg:mb-1 pt-7"
        >
          See, One price. Simple.
        </div>

        <!-- Sixth Row: Button -->
        <div
          class="ElementButtonMediumFilled w-full max-w-[189px] h-[35px] mx-auto relative"
        >
          <div
            class="Bg w-full max-w-[189px] h-9 left-0 top-0 absolute bg-[#111b47] rounded-sm"
          ></div>
          <div
            class="ButtonLabel w-full max-w-[189px] left-0 top-[4px] absolute text-center text-white text-sm font-medium font-['Roboto'] leading-normal md:pt-1"
          >
            Purchase Now
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
};
</script>

<style scoped>
footer {
  background-position: center center;
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
}
</style>

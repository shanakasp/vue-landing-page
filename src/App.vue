<template>
  <NavBar />
  <Body1 />
  <Body2 />
  <Body3 />
  <Body4 />
  <Body5 />
  <Footer />
</template>

<script>
import NavBar from "./components/NavBar.vue";
import Body1 from "./components/Body1.vue";
import Body2 from "./components/Body2.vue";
import Body3 from "./components/Body3.vue";
import Body4 from "./components/Body4.vue";
import Body5 from "./components/Body5.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    NavBar,
    Body1,
    Body2,
    Body3,
    Body4,
    Body5,
    Footer,
  },
};
</script>

<style>
#app {
}
</style>

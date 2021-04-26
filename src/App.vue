<template>
  <div>
    <Navbar />
    <Hero />
    <AppFooter />
  </div>
</template>

<script>
import Navbar from "./components/navigation/Navbar";
import Hero from "./components/Hero";
import AppFooter from "./components/navigation/Footer";
export default {
  name: "App",
  components: {
    Navbar,
    Hero,
    AppFooter,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap");

:root {
  --primary: #002744;
  --primary-text: #003150;
  --primary-light-text: #647e8f;
  --white: rgb(253, 251, 251);
}

.bg-dark {
  background-color: var(--primary) !important;
}

.white-text {
  color: var(--white);
}
</style>

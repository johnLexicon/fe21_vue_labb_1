<template>
  <div>
    <Navbar />
    <Hero />
  </div>
</template>

<script>
import Navbar from "./components/navigation/Navbar";
import Hero from "./components/Hero";
export default {
  name: "App",
  components: {
    Navbar,
    Hero,
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

.white-text {
  color: var(--white);
}
</style>

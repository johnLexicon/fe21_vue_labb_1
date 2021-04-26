<template>
  <div>
    <Navbar />
  </div>
</template>

<script>
import Navbar from "./components/navigation/Navbar";
export default {
  name: "App",
  components: {
    Navbar,
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
</style>

<template>
  <section id="hero">
    <div
      class="layer d-flex flex-column justify-content-center align-items-center"
    >
      <p class="display-1 white-text">L'orologio d'adesso</p>
      <p class="hero-text display-6 white-text text-center">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eveniet
        necessitatibus fugiat eaque porro eius quos quas dignissimos ipsum
        aspernatur! At necessitatibus impedit quis repellendus nisi incidunt
        adipisci, culpa ut ipsum.
      </p>
      <button
        v-on:click="action"
        class="btn btn-lg btn-light btn-outline-secondary"
      >
        Call to Action
      </button>
    </div>
  </section>
</template>

<script>
export default {
  methods: {
    action() {
      console.log("Action button clicked!!!");
    },
  },
};
</script>

<style scoped>
#hero {
  background-image: url("/img/watches.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 100vh;
}

#hero .layer {
  background-color: rgb(66, 66, 155, 0.3);
  height: inherit; /* Inherits from hero section (100vh) */
}

#hero h1 {
  font-size: 2rem;
}

.height-fix {
  padding-top: 74px;
}

@media screen and (min-width: 768px) {
  .hero-text {
    width: 75%;
  }
}

@media screen and (min-width: 2300px) {
  .hero-text {
    width: 50%;
  }
}
</style>
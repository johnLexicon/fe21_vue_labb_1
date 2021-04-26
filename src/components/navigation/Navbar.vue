<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a href="#" class="navbar-brand logo-text">L'orologio d'adesso</a>
      <button
        class="navbar-toggler"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        type="button"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="navbarNav" class="collapse navbar-collapse">
        <div class="navbar-nav ms-auto">
          <a href="#" class="nav-link">Home</a>
          <a href="/about.html" class="nav-link">About</a>
          <a href="/contact.html" class="nav-link">Contact</a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
.logo-text {
  font-family: "Dancing Script", cursive;
  font-size: 2rem;
}

.bg-dark {
  background-color: var(--primary) !important;
}
</style>
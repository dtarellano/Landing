<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-center">
      <a class="navbar-item">
        Home
      </a>
      <a class="navbar-item">
        About
      </a>
      <a class="navbar-item">
        Pricing
      </a>
      <a class="navbar-item">
        Contact
      </a>
    </div>
    <div class="navbar-end">
      <div class="navbar-item">
        <button class="button">Login</button>
      </div>
      <div class="navbar-item">
        <button class="button is-primary">Try Free</button>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="css">
  .navbar {
    width: 90%;
    margin:auto;
  }
  .navbar-center {
    display:flex;
    width: 10%;
    margin: auto;
  }
</style>

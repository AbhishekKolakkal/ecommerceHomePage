<template>
  <nav class="navbar navbar-expand-md navbar-light py-4" id="main-nav">
    <div class="container">
      <a href="#home" class="navbar-brand">
        <img src="../assets/mlogo.png" width="50" height="50" alt="" />
        <h3 class="d-inline align-middle">Mizuxe</h3>
      </a>
      <button
        class="navbar-toggler"
        data-toggle="collapse"
        data-target="#navbarCollapse"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <ul class="navbar-nav ml-auto font-weight-bold">
          <li class="nav-item">
            <a href="#home" class="nav-link">What's New</a>
          </li>
          <li class="nav-item">
            <a href="#home" class="nav-link">Brands</a>
          </li>
          <li class="nav-item">
            <a href="#home" class="nav-link">Western Wear</a>
          </li>
          <li class="nav-item">
            <a href="#home" class="nav-link">Indian Wear</a>
          </li>
          <li class="nav-item">
            <a href="#home" class="nav-link">Bags</a>
          </li>
          <li class="nav-item">
            <a href="#home" class="nav-link">Shoes</a>
          </li>
          <li class="nav-item">
            <a href="#about" class="nav-link">Jewellery</a>
          </li>
          <li class="nav-item">
            <a href="#authors" class="nav-link">Sale</a>
          </li>
          <li class="nav-item">
            <a href="#contact" class="nav-link">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "AppNavBar",
};
</script>

<style scoped>
li {
  padding-left: 10px;
  padding-right: 10px;
}
</style>

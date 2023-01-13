<template>
  <nav class="navbar navbar-expand-lg navbar-light">
    <div class="container">
      <a class="navbar-brand" href="#">PASIFIC</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item ">
            <router-link class="nav-link" to="/">Home</router-link>
          </li>

          <li class="nav-item">
            <router-link class="nav-link" to="/product">Product</router-link>
          </li>
          <li class="nav-item ">
            <router-link class="nav-link" to="/logreg">Login/Register</router-link>
          </li>
        </ul>
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <router-link class="nav-link" to="/keranjang">
            Keranjang</router-link><b-icon-bag></b-icon-bag>
            <span class ="badge-badge-succes ml=2">0</span>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
  
<script>
export default {
  name: "Navbar",
};
</script>
  
 
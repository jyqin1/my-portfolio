<template>
  <nav id="navbar" class="black navbar navbar-expand-lg fixed-top">
    <router-link id="nav-logo" class="navbar-brand" to="/">Jeffrey Qin</router-link>
    <button class="navbar-toggler" id="nav-btn" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
      <span class="navbar-btn"><i class="fa fa-bars" aria-hidden="true"></i></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="collapsibleNavbar">
      <ul id="nav-ul" class="navbar-nav">
        <li class="nav-item navigation-list">
          <router-link class="nav-link nav-custom-link" to="/">Home</router-link>
        </li>
        <li class="nav-item navigation-list">
          <router-link class="nav-link nav-custom-link" to="/about">About</router-link>
        </li>
        <li class="nav-item navigation-list">
          <router-link class="nav-link nav-custom-link" to="/portfolio">Portfolio</router-link>
        </li>
        <li class="nav-item navigation-list">
          <router-link class="nav-link nav-custom-link" to="/contact">Contact</router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'AppNavbar'
}
</script>

<style scoped>
#navbar {
  font-family: Roboto, sans-serif;
  background-size: cover;
  background-color: rgba(255, 255, 255, 0.8);
  padding: 15px 20px;
  transition: all 0.5s ease;
}

#nav-logo {
  font-size: 24px;
  color: #000000;
  text-transform: uppercase;
  font-weight: bolder;
}

.nav-custom-link {
  font-weight: bold;
  color: #000000 !important;
  text-transform: uppercase;
}

.nav-custom-link:hover {
  color: #FFFFFF !important;
  background-color: #000000;
}
</style>

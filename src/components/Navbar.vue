<template>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/projects">Projects</router-link>
    <router-link to="/contact">Contact</router-link>
  </nav>
</template>

<script>
export default {
  name: 'AppNavbar'
}
</script>

<style scoped>
nav {
  display: flex;
  justify-content: space-around;
  padding: 10px;
  background-color: #f2f2f2;
}
router-link {
  text-decoration: none;
  padding: 10px;
  color: #333;
}
router-link:hover {
  color: #555;
}
</style>

<template>
  <div class="projects">
    <h1>Projects</h1>
    <ul>
      <li><a href="#">Project 1</a>: Description of Project 1...</li>
      <li><a href="#">Project 2</a>: Description of Project 2...</li>
      <li><a href="#">Project 3</a>: Description of Project 3...</li>
      <!-- Add more projects as needed -->
    </ul>
  </div>
</template>

<script>
export default {
  name: 'AppProjects'
}
</script>

<style scoped>
.projects {
  padding: 20px;
  text-align: center;
}
.projects ul {
  list-style: none;
  padding: 0;
}
.projects li {
  margin-bottom: 10px;
}
</style>

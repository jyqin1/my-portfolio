<template>
  <div class="home">
    <h1>About Me</h1>
    <img :src="profileImage" alt="Profile Picture" class="profile-pic">
    <p>Hello! I'm a dedicated and detail-oriented developer, here is a little about my background, skills, and what I bring to the table.</p>
  </div>
</template>

<script>
export default {
  name: 'AppAbout',
  data() {
    return {
      profileImage: require('@/assets/pfp2.jpg')
    }
  }
}
</script>

<style scoped>
.home {
  padding: 20px;
  text-align: center;
}

.profile-pic {
  width: 400px;
  height: 500px;
  border-radius: 60%;
  object-fit: cover;
  object-position: center;
  margin-bottom: 20px;
}
</style>

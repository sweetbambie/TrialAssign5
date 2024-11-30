<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
  <div class="header">
    <div class="logo">
      <img src="/src/assets/transparentLogo.png" class="logo"/>
    </div>
    <div class="buttons">
      <RouterLink to="/register" class="button register">Register</RouterLink>
      <RouterLink to="/login" class="button login">Login</RouterLink>
    </div>
  </div>    
</template>

<style scoped>
html, body {
  height: 100%;
  margin: 0;
  padding: 0;
  width: 100%;
}

.header {
  background-image: linear-gradient(rgba(78, 25, 20, 0.7),rgba(78,25,20,0.7)),url('/src/assets/Background.png');
  background-position: center center;
  background-size: cover;
  min-width: 100%;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-end;
}

.logo {
  max-width: 80%;
  margin-bottom: 20px;
}

.buttons {
  display: flex;
  gap: 20px;
  margin-bottom: 50px;
}

.button {
  padding: 10px 20px;
  background-color: rgb(255, 255, 255);
  color: black;
  border-radius: 5px;
  cursor: pointer;
}

footer {
  padding: 20px;
  background-color: #333;
  color: white;
  text-align: center;
}
</style>
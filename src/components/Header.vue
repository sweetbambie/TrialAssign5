<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
<div class="header">
    <nav>
        <img src="/src/assets/transparentLogo.png" class="logo"/>
            <div class="buttons">
                <RouterLink to="/register" class="button register">Register</RouterLink>
                <RouterLink to="/login" class="button login">Login</RouterLink>
            </div>
        </nav>
        <!-- <div class="header-content">
            <h1>Nitche Feminine Movies, Shows, and more.</h1>
            <h3>Watch anytime and anywhere.</h3>
            <p>Ready to watch? Type in your email to create your account.</p>
        </div> -->
    </div>
</template>

<style scoped>
/* html, body {
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

.header-content {
    font-size: 20px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    margin-top: 100px;
} */

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
</style>
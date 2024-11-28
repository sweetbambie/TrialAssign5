<template>
    <div class ='header'>
        <img :src="logo" class="logo" alt="Logo">
            <div>
                <button class="language-btn">English</button>
                <button>Sign In</button>
                <button>Sign Out</button>
            </div>
    </div>
</template>

<script>
import logo from '@/assets/transparentLogo.png';
export default {
  // No need to define data, just return the imported logo
  computed: {
    logo() {
      return logo;
    }
  }
};
</script>

<style scoped>
    .header{
        width: 100%;
        height: auto;
        background:rgba(78, 25, 20, 0.7), url(@/assets/Background.png);
        background-size: cover;
        background-position: center;
        padding: 10px 8%;
        position: relative;
    }
</style>
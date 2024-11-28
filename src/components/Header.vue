<template>
    <div class ='header'>
        <RouterLink to='/Sign In' class="button"></RouterLink>
        <RouterLink to='/Sign Out' class="button"></RouterLink>
    </div>
</template>

<script>
import { RouterLink } from 'vue-router';
// import logo from '@/assets/transparentLogo.png';
</script>

<style scoped>
    .header{
        width: 100%;
        height: auto;
        background:rgba(78, 25, 20, 0.7), url('src/assets/img/transparentLogo.png');
        background-size: cover;
        background-position: center;
        padding: 10px 8%;
        position: relative;
    }
</style>
<script setup>
import { RouterLink } from 'vue-router';
</script>


<template>
    <div class="container">
        <div class="nav-left">
            <div class="logo">
                <img src="../assets/logo.jpeg" alt="">
            </div>
        </div>
        <div class="nav-right">
            <div class="nav-item">
                <RouterLink class="nav-item" to="home">Home</RouterLink>
                <RouterLink class="nav-item" to="about">About</RouterLink>
            </div>
        </div>
    </div>
</template>

<style>
.logo img{
    height: 10vh;
    width: 60px;
}
.container{
}
</style>
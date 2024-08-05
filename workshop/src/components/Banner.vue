<template>

    <section class="banner-section">
        <form>
            <div class="search-input">
            <input 
                type="text" 
                required="true"
            >
            <span>Search movie</span>
            </div>
        </form>
        <div class="container-banner-img">
            <img :src="img" alt="header-img">
        </div>
    </section>
</template>

<script setup lang="ts">
import svgImage from '@/assets/images/header-img.svg'

const img = svgImage;
</script>

<style lang="scss" scoped>
.banner-section {
    width: 100%;
    height: 50vh;
    background-image: url(../assets/images/banner-bg.png);
    background-size: cover;
    display: flex;
    justify-content: space-between;
    align-items: center;
    
    form {
        .search-input {
        
            }
        }


    }

</style>
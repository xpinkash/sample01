<template>
    <div class="header">
        <h1 class="mainLogo"><nuxt-link to="/"><img src="~/assets/image/logo.png"></nuxt-link></h1>
        <ul class="navigation">
            <li><nuxt-link to="/menu">Menu</nuxt-link></li>
            <li><nuxt-link to="">My Bag</nuxt-link></li>
            <li><nuxt-link to=""> My Favorites</nuxt-link></li>
            <li><nuxt-link to="">Order Tracker</nuxt-link></li>
            <li><nuxt-link to="">My Account</nuxt-link></li>
            <li><nuxt-link to="">Login</nuxt-link></li>
        </ul>
    </div>
</template>


<style scoped>
    .header {
        background: #EC0000;
        padding: 10px;
        overflow: hidden;
    }
    .mainLogo {
        float: left;
    }
    .mainLogo img{
        width: 175px;
    }
    .navigation {
        float: right;
        overflow: hidden;
        margin: 15px 0 0 0;
    }
    .navigation li {
        float: left;
        list-style-type: none;
    }
    .navigation li a{
        padding: 5px 10px;
        color: #fff;
        text-decoration: none;
    }
</style>



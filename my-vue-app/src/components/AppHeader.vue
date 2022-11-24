<script>

import AppLogo from './AppLogo.vue';

export default {
    name: 'AppHeader',
    components: {
        AppLogo
    }
}
</script>

<template>

    <header>
        <AppLogo />
        <ul class="main-nav">
            <li><a href="#">CHARACTERS</a></li>
            <li><a href="#">COMICS</a></li>
            <li><a href="#">MOVIES</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">GAMES</a></li>
            <li><a href="#">COLLECTIBLES</a></li>
            <li><a href="#">VIDEOS</a></li>
            <li><a href="#">FANS</a></li>
            <li><a href="#">NEWS</a></li>
            <li><a href="#">SHOP</a></li>

        </ul>

    </header>

</template>

<style scoped>
header {
    display: flex;
}

.main-nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

a {
    text-decoration: none;
    color: black;
}

li {
    list-style: none;
    padding: 10px;

}
</style>

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
        <div class="container">
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
        </div>
    </header>

</template>

<style scoped>
.container {
    max-width: 1000px;
    margin: auto;
    display: flex;
}

header {
    display: flex;
    justify-content: space-between;
    background-color: white;
    padding: 20px;
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

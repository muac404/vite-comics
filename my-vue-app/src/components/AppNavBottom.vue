<script>
export default {
    name: 'AppNavBottom',
}
</script>

<template>
    <section class="bottom-nav">
        <div class="container">
            <div class="card">
                <div class="dc-icon">
                    <img src="../assets/buy-comics-digital-comics.png" alt="comics">
                </div>
                <h4>DIGITAL COMICS</h4>
            </div>

            <div class="card">
                <div class="dc-icon">
                    <img src="../assets/buy-comics-merchandise.png" alt="comics">
                </div>
                <h4>DC MERCHANDISE</h4>
            </div>

            <div class="card">
                <div class="dc-icon">
                    <img src="../assets/buy-comics-subscriptions.png" alt="comics">
                </div>
                <h4>SUBSCRIPTION</h4>
            </div>

            <div class="card">
                <div class="dc-icon">
                    <img src="../assets/buy-comics-shop-locator.png" alt="comics">
                </div>
                <h4>COMIC SHOP LOCATOR</h4>
            </div>

            <div class="card">
                <div class="dc-icon">
                    <img src="../assets/buy-dc-power-visa.svg" alt="comics">
                </div>
                <h4>DC POWER VISA</h4>
            </div>
        </div>
    </section>
</template>

<style scoped>
.bottom-nav {
    background-color: #0282f9;

}

.container {
    max-width: 1100px;
    margin: auto;
    display: flex;

}

.card {
    display: flex;
    align-items: center;
    margin: 10px;
    cursor: pointer;

}

h4 {
    font-size: 12px;
    font-weight: 400;
}

.dc-icon img {
    height: 60px;
    margin: 10px;
}
</style>
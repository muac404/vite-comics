<script>
export default {
    name: 'AppFooterBottom',
}
</script>

<template>
    <section class="footer-bottom">
        <div class="container">
            <div class="l-footer">
                <button class="sign-up-btn">SIGN UP NOW!</button>
            </div>
            <div class="r-footer">
                <h3>FOLLOW US</h3>
                <div class="icon">
                    <img src="../assets/footer-facebook.png" alt="">
                </div>
                <div class="icon">
                    <img src="../assets/footer-twitter.png" alt="">
                </div>
                <div class="icon">
                    <img src="../assets/footer-youtube.png" alt="">
                </div>
            </div>
        </div>
    </section>

</template>

<style scoped>
.container {
    max-width: 1200px;
    margin: auto;
    display: flex;
    justify-content: space-between
}

.l-footer {
    display: flex;
    align-items: center;

}

.r-footer {
    display: flex;
    align-items: center;

}

.sign-up-btn {
    padding: 10px;
    background-color: transparent;
    color: white;
    border: 1px solid #0282f9;
    cursor: pointer;
}

.sign-up-btn:hover {
    background-color: black;
}

h3 {
    color: #0282f9;
    margin-right: 15px;
}

.icon {
    margin-left: 10px;
    cursor: pointer;
}
</style>
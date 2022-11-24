<script>
export default {
    name: 'AppFooterTop',
}
</script>

<template>
    <section class="footer-top">
        <div class="container">
            <div class="footer-l">
                <div class="dc-comics-&-shop">
                    <ul>
                        <li>
                            <h3>DC COMICS</h3>
                        </li>
                        <li><a href="#"></a>Characters</li>
                        <li><a href="#"></a>Comics</li>
                        <li><a href="#"></a>Movies</li>
                        <li><a href="#"></a>TV</li>
                        <li><a href="#"></a>Games</li>
                        <li><a href="#"></a>Videos</li>
                        <li><a href="#"></a>News</li>
                    </ul>
                    <ul>
                        <li>
                            <h3>SHOP</h3>
                        </li>
                        <li><a href="#"></a>Shop DC</li>
                        <li><a href="#"></a>Shop DC Collectibles</li>

                    </ul>
                </div>

                <div class="dc-policy">
                    <ul>
                        <li>
                            <h3>DC</h3>
                        </li>
                        <li><a href="#"></a>Terms Of Use</li>
                        <li><a href="#"></a>Privacy policy (New)</li>
                        <li><a href="#"></a>Ad Choices</li>
                        <li><a href="#"></a>Advertising</li>
                        <li><a href="#"></a>Jobs</li>
                        <li><a href="#"></a>Subscriptions</li>
                        <li><a href="#"></a>Talent Workshops</li>
                        <li><a href="#"></a>CPSC Certificates</li>
                        <li><a href="#"></a>Ratings</li>
                        <li><a href="#"></a>Shop Help</li>
                        <li><a href="#"></a>Contact Us</li>

                    </ul>

                </div>

                <div class="partners">
                    <ul>
                        <li>
                            <h3>SITES</h3>
                        </li>
                        <li><a href="#"></a>DC</li>
                        <li><a href="#"></a>MAD Magazine</li>
                        <li><a href="#"></a>DC Kids</li>
                        <li><a href="#"></a>DC Universe</li>
                        <li><a href="#"></a>DC Power Visa</li>

                    </ul>

                </div>
            </div>
            <div class="footer-r">
                <img src="../assets/dc-logo-bg.png" alt="logo-bg">
            </div>

        </div>
    </section>
</template>

<style scoped>
.footer-top {
    background-image: url("../assets/footer-bg.jpg");

}

img {
    width: 300px;
}

.container {
    max-width: 1200px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;


}

ul {
    margin: 0;
    padding: 0;
}

li {
    list-style: none;
    padding: 0;
    margin-right: 40px;

}

li:not(:first-child) {
    cursor: pointer;
    color: grey;
}

li:not(:first-child):hover {
    cursor: pointer;
    color: white;
}

h3 {
    margin-top: 5px;
    margin-bottom: 5px;
    font-weight: 400;
}

.footer-l {
    display: flex;
}

.footer-r {
    padding: 20px;
}
</style>
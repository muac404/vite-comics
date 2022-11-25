<script>
export default {
  name: "AppNavBottom",
};
</script>

<template>
  <section class="bottom-nav">
    <div class="container">
      <div class="card">
        <div class="dc-icon">
          <img src="../assets/buy-comics-digital-comics.png" alt="comics" />
        </div>
        <h4>DIGITAL COMICS</h4>
      </div>

      <div class="card">
        <div class="dc-icon">
          <img src="../assets/buy-comics-merchandise.png" alt="comics" />
        </div>
        <h4>DC MERCHANDISE</h4>
      </div>

      <div class="card">
        <div class="dc-icon">
          <img src="../assets/buy-comics-subscriptions.png" alt="comics" />
        </div>
        <h4>SUBSCRIPTION</h4>
      </div>

      <div class="card">
        <div class="dc-icon">
          <img src="../assets/buy-comics-shop-locator.png" alt="comics" />
        </div>
        <h4>COMIC SHOP LOCATOR</h4>
      </div>

      <div class="card">
        <div class="dc-icon">
          <img src="../assets/buy-dc-power-visa.svg" alt="comics" />
        </div>
        <h4>DC POWER VISA</h4>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.bottom-nav {
  background-color: #0282f9;
}

.container {
  max-width: 1200px;
  margin: auto;
  display: flex;
  justify-content: center;
  flex-grow: 1;
}

.card {
  display: flex;
  align-items: center;
  width: calc(100% / 5);
  margin: 20px;
  cursor: pointer;
  transition: all 0.3s;
  &:hover {
    scale: 1.1;
  }
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

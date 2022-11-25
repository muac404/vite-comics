<script>
export default {
  name: "AppComicCard",
  props: {
    thumb: String,
    price: String,
    series: String,
    type: String,
  },
};
</script>

<template>
  <div class="comic-card">
    <div class="comic-img">
      <img :src="thumb" alt="type" />
    </div>
    <div>{{ series }}</div>
  </div>
</template>

<style lang="scss" scoped>
.comic-img img {
  width: 150px;
  height: 150px;
  object-fit: cover;
  object-position: top;
}

.comic-card {
  width: 150px;
}
</style>

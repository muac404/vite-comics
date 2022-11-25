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
    <div class="title-card">{{ series }}</div>
  </div>
</template>

<style lang="scss" scoped>
.comic-img img {
  width: 150px;
  height: 150px;
  object-fit: cover;
  object-position: top;
  &:hover {
    filter: grayscale(100);
    scale: 1.1;
  }
}

.comic-card {
  width: 150px;
  cursor: pointer;
  transition: all 0.3s;
  &:hover {
    scale: 1.1;
  }
}

.title-card {
  text-transform: uppercase;
}
</style>

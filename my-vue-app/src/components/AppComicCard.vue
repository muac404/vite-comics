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
    <img :src="thumb" alt="type" />
    <h4>{{ series }}</h4>
  </div>
</template>

<style scoped></style>

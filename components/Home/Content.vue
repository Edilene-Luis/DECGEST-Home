<template>
  <div
    class="d-flex w-100 justify-content-between align-items-center flex-wrap"
    :class="idx % 2 == 0 ? 'flex-row-reverse' : 'flex-row'"
  >
    <div class="img-container">
      <img :src="img" alt="img-content-DECGEST" class="h-100 w-100" />
    </div>
    <div class="w-50">
      <h3 class="text-uppercase">{{ title }}</h3>
      <p>{{ text }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    ['title']: String,
    ['text']: String,
    ['img']: String,
    ['idx']: Number,
  },
}
</script>

<style scoped>
.img-container {
  /* width: 300px !important; */
  height: 300px !important;
}
.img-container img {
  object-fit: cover;
  border-radius: 45px !important;
}
p {
  font-size: 12px;
}
</style>

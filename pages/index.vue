<template>
  <div>
    <h1 class="main-title">hi, i'm index</h1>
    <nuxt-link to="about">about</nuxt-link>
    <br>
    <nuxt-link to="list">list</nuxt-link>
  </div>
</template>

<script>
export default {
  name: "index"
}
</script>

<style scoped lang="scss">
.main-title {
  color: $color-main;
}
</style>

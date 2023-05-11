<script setup>
import Header from "../components/Header.vue";
import Content from "../components/Content.vue";
</script>

<template>
  <div class="screen-bg">
    <Header />
    <Content />
  </div>
</template>

<style lang="scss" scoped>
.screen-bg {
  display: flex;
  flex-direction: column;
  /* height: 100%; */
  width: 100%;
  background: url(@/assets/images/bg.png);
}
</style>

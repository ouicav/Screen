<script setup>
import TopTitle from "../TopTitle.vue";
</script>
<template>
  <div class="right">
    <div class="right-top">
      <TopTitle />
      <div class="parent">
        <div class="div1"></div>
        <div class="div2">
          <div class="div2-right-top">111</div>
          <div class="right-one-block"></div>
        </div>
        <div class="div3"></div>
        <div class="div4">
          <div class="div2-right-top">111</div>
          <div class="right-one-block"></div>
        </div>
        <div class="div5"></div>
      </div>
    </div>
    <div class="right-bottom"></div>
  </div>
</template>
<style lang="scss" scoped>
.right {
  display: flex;
  flex-direction: column;
  // width: 430px;
  // height: 977px;

  .right-top {
    width: 430px;
    height: 450px;
    background-image: url(@/assets/images/资金进度.png);
    .parent {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      grid-template-rows: repeat(3, 1fr);
      grid-column-gap: 0px;
      grid-row-gap: 0px;
      height: 400px;
      border: 1px solid red;
    }

    .div1 {
      width: 124px;
      height: 100px;
      grid-area: 1 / 1 / 2 / 2;
      background-image: url(@/assets/images/right-one-circle.png);
    }
    .div2 {
      grid-area: 1 / 2 / 2 / 3;
    }
    .div3 {
      width: 124px;
      height: 100px;
      background-image: url(@/assets/images/right-one-circle.png);
      grid-area: 2 / 1 / 3 / 2;
    }
    .div4 {
      grid-area: 2 / 2 / 3 / 3;
    }
    .div5 {
      grid-area: 3 / 1 / 4 / 3;
    }
    .div6 {
      grid-area: 4 / 1 / 5 / 3;
    }
    .div2-right-top {
    }
    .right-one-block {
      width: 216px;
      height: 24px;
      background-image: url(@/assets/images/right-one-block.png);
    }
  }

  .right-bottom {
    width: 428px;
    height: 435px;
    margin-top: 62px;
    margin-left: 24px;
    background-image: url(@/assets/images/工程进度.png);
  }
}
</style>

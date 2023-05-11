<script setup>
import TopTitle from "../TopTitle.vue";
</script>
<template>
  <div class="left">
    <div class="left-content">
      <TopTitle />
      <div class="left-arrowhead">
        <div class="left-arrowhead-top">
          <div class="left-project-stage-process"></div>
          <div class="left-big-arrowhead"></div>
          <div class="left-project-stage-process"></div>
          <div class="left-big-arrowhead"></div>
          <div class="left-project-stage-process"></div>
        </div>
      </div>
      <div class="left-arrowhead-center"></div>
      <div class="left-arrowhead-bottom"></div>
    </div>
    <div class="left-circle"></div>
    <div class="left-line"></div>
    <div class="left-line"></div>
    <div class="left-line"></div>
    <div class="left-line"></div>
    <div class="project-funds">
      <div class="project-funds-left"></div>
      <div class="project-funds-right">
        <div class="project-funds-right-img"></div>
      </div>
      <div class="project-funds-circle"></div>
      <div class="project-funds-form"></div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.left {
  /* display: flex;
  flex-direction: column; */
  /* border: 1px solid red; */
  width: 428px;
  height: 961px;
  background-image: url(@/assets/images/bg_left.png);

  &-content {
    padding-left: 73px;
  }

  &-arrowhead {
    margin-left: 6px;
    width: 16px;
    height: 18px;
    border: 1px solid blanchedalmond;
    background-image: url(@/assets/images/left-arrowhead.png);

    &-top {
      display: flex;
      width: 416px;
      justify-content: space-between;
      align-items: center;
      border: 1px solid blueviolet;
      padding-top: 30px;

      .left-project-stage-process {
        width: 99px;
        height: 72px;
        background-image: url(@/assets/images/leftProjectStageProcess.png);
      }

      .left-big-arrowhead {
        width: 43px;
        height: 32px;
        background-image: url(@/assets/images/leftBigArrowhead.png);
      }
    }

    &-center {
      margin-left: 57%;
      margin-top: 96px;
      width: 27px;
      height: 15px;
      /* border:1px solid red; */
      background-image: url(@/assets/images/underTheArrow.png);
    }
    &-bottom {
      width: 416px;
      height: 54px;
      background-image: url(@/assets/images/leftArrowheadBottom.png);
    }
  }
  &-circle {
    width: 283px;
    height: 142px;
    margin-left: 142px;
    background-image: url(@/assets/images/leftCircle.png);
  }

  &-line {
    margin-left: 80px;
    margin-top: 21px;
    width: 386px;
    height: 18px;
    background-image: url(@/assets/images/line.png);
  }
  .project-funds {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: 1fr auto;
    grid-column-gap: 0px;
    grid-row-gap: 0px;
    margin-left: 37px;

    &-left,
    &-right-img {
      border: 1px solid red;
      width: 141px;
      height: 38px;
      background-image: url(@/assets/images/projectFundsLeft.png);
      margin-bottom: 16px;
    }

    &-left {
      margin-left: 10px;
      grid-area: 1 / 1 / 2 / 2;
      height: 38px;
    }
    &-right {
      grid-area: 1 / 2 / 2 / 3;
      display: flex;
      justify-content: center;
    }

    &-circle {
      grid-area: 2 / 1 / 3 / 2;
      width: 150px;
      height: 150px;
      background-image: url(@/assets/images/projectFundsCircle.png);
    }
    &-form {
      grid-area: 2 / 2 / 3 / 3;
    }
  }
}
</style>

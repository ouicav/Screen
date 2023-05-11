<script setup>
</script>
<template>
  <div class="header">
    <div class="title">
      <div>青海省生态环境保护修复项目平台</div>
      <div class="title-t-c-gradient"></div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.header {
  position:fixed;
  width:100%;
  display: flex;
  flex-direction: column;
  /* height: 103px; */
  background-image: url(@/assets/images/bg_header.png);

  .title {
    border: 1px solid red;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding-top: 22px;
    /* padding-left: 705px; */
    font-size: 36px;
    font-family: PangMenZhengDao;
    color: #5bbbfe;
    line-height: 41px;
    letter-spacing: 1px;
    text-shadow: 0px 2px 0px #2e5e80;
    background: linear-gradient(180deg, #ffffff 0%, #5bbbfe 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    &-t-c-gradient {
      width: 218px;
      height: 35px;
      background-image: url(@/assets/images/TopTimeGradient.png);
    }
  }

  .header-bottom {
    margin: 69px auto 0;
    width: 216px;
    height: 33px;
    background: linear-gradient(360deg, #2687d3 0%, rgba(85, 239, 255, 0) 100%);
    border: 1px solid;
    border-image: linear-gradient(
        180deg,
        rgba(0, 175, 255, 0),
        rgba(0, 175, 255, 1)
      )
      1 1;
  }
}
</style>

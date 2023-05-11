<script setup>
import ContentLeft from "./Content/ContentLeft.vue";
import ContentCenter from "./Content/ContentCenter.vue";
import ContentRight from "./Content/ContentRight.vue";
</script>
<template>
  <div class="content">
    <ContentLeft />
    <ContentCenter />
    <ContentRight />
  </div>
</template>

<style lang="scss" scoped>
.content {
  display: flex;
  height:calc(100vh - 103px);
  padding-top:103px;
  border:1px solid yellow;
}
</style>

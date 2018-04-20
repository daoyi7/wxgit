<template>
  <div class="container">
    <div class="main">
      3232
    </div>
    <div class="git-foot">
      <git-foot></git-foot>
    </div>
  </div>
</template>

<script>
import gitFoot from "@/components/foot";

export default {
  components: {
    gitFoot
  }
};
</script>

<style scoped>
.main {
  flex: 1;
}
.git-foot {
  flex: 0 0 80rpx;
  border-top: 1rpx solid rgba(27,31,35,0.2);
}
</style>

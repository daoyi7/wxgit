<template>
  <div class="foot">
    <div class="item">
      <a href="/pages/counter/main" class="news">News</a>
    </div>
    <div class="item">
      <a href="/pages/counter/main" class="notifications">Notifications</a>
    </div>
    <div class="item">
      <a href="/pages/counter/main" class="profile">Profile</a>
    </div>
  </div>
</template>
<script>
export default {
}
</script>
<style scoped>
.foot {
  padding: 0 12px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #fff;
}
.item {
  flex: 1;
  text-align: center;
  line-height: 80rpx;
}
.item a {
  font-size: 20rpx;
  color: rgba(27,31,35,0.8);
}
</style>


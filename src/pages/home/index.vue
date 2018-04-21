<template>
  <div class="container">
    <div class="main">
      <input v-model="keyword" @bindconfirm="search" placeholder="你想搜点啥？" />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      keyword: ""
    };
  },
  method: {
    input(e) {
      this.keyword = e.detail.value
      console.log(e.datail.value)
    },
    search() {
      console.log(222)
    }
  },
  watch: {
    keyword(val, newVal) {
      console.log(value, newValue)
    }
  }
};
</script>

<style scoped>
.main {
  padding: 40px;
  height: 100%;
}
input {
  display: block;
  border: 1rpx solid rgba(27, 31, 35, 0.8);
  height: 35rpx;
  padding: 8rpx;
  color: rgba(27, 31, 35, 0.8);
}
</style>

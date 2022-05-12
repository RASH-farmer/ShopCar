<template>
  <div class="my-good-item">
    <div class="left">
        <div class="left-inp custom-control custom-checkbox">
        <input type="checkbox" class="custom-control-input" id="input">
        <label for="input" class="custom-control-label">
          <img src="../assets/logo.png" alt="">
        </label>
      </div>
    </div>
    <div class="right">
      <div class="top">
        商品名字
      </div>
      <div class="bottom">
       <div class="price">200</div>
      <span>数量组件</span>
      </div>
  
    </div>

    </div>
</template>

<script>
export default {
  name: "WorkspaceJsonMyGoods",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

  <style lang="less" scoped>
.my-good-item {
  display: flex;
  padding: 10px;
  border-bottom: 1px solid #ccc;
  .left {
    width: 120px;
    .left-inp {
      display: flex;
      justify-content: space-around;
      align-items: center;
    }
    img {
      width: 100px;
      height: 100px;
      margin-right: 8px;
      border-radius: 10px;
    }
  }
  .right {
    flex: 1;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    .top {
      font-size: 14px;
      font-weight: 700;
    }
    .bottom {
      display: flex;
      justify-content: space-between;
      padding: 5px 0;
      align-items: center;
      .price {
        color: red;
        font-weight: bold;
      }
    }
  }
}
</style>

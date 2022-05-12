<template>
  <div>
    <my-header></my-header>
    <my-foot></my-foot>
    <my-goods></my-goods>
    <!-- <my-count></my-count> -->
  </div>
</template>

<script>
import MyHeader from "@/components/MyHeader.vue";
import MyFoot from "@/components/MyFoot.vue";
import MyGoods from "@/components/MyGoods.vue";
// import MyCount from "@/components/MyCount.vue";
export default {
  components: { MyHeader, MyFoot, MyGoods },
  name: "WorkspaceJsonHomeView",

  data() {
    return {};
  },

  mounted() {},

  methods: {},
};
</script>

<style lang="less">
</style>
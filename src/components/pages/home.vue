<template>
  <div class="body">
    <!-- 表头 -->
    <header-bar></header-bar>
    <!-- 表头 -->
    <!-- 主页banner -->
    <div class="banner">
      <div class="bannertext">
        <h1 class="bannerTitle">世界上最便宜的SSL证书提供商</h1>
        <h3 class="bannerInfo">我们提供14天免费试用和30天免费退款</h3>
        <el-button icon="el-icon-lock" class="bannerBtn">加入SSL</el-button>
      </div>
    </div>
    <!-- 主页banner -->

    <div class="productList">
      <el-row :gutter="12" class="productListBox">
        <el-col :span="8">
          <el-card shadow="hover" class="productListCard">
            <p>Comodo Positive DV Single SSL</p>
            <p>保护 www.钥.com 或 钥.com</p>
            
            <el-rate
              v-model="value"
              disabled
              show-score
              :icon-classes="iconClasses"
              void-icon-class="el-icon-lock"
              text-color="#ff9900"
            ></el-rate>

          </el-card>
        </el-col>
        <el-col :span="8">
          <el-card shadow="hover" class="productListCard">鼠标悬浮时显示</el-card>
        </el-col>
        <el-col :span="8">
          <el-card shadow="hover" class="productListCard">从不显示</el-card>
        </el-col>
      </el-row>
    </div>
    <foot-bar></foot-bar>
  </div>
</template>
<script>
import headerBar from "@/components/common/HeaderBar";
import footBar from "@/components/common/FootBar";
export default {
  data() {
    return {
      value: 3.5
    };
  },
  mounted: function() {},
  components: {
    headerBar,
    footBar
  }
};
</script>
<style scoped>
.banner {
  background-image: linear-gradient(to right, #051146, #243a9c);
  height: 300px;
  padding: 50px 0;
}
.bannertext {
  max-width: 1200px;
  height: 300px;
  margin: auto;
}
.bannerTitle {
  color: #ffffff;
  line-height: 100px;
  margin: 0;
  font-weight: 100;
}
.bannerInfo {
  color: rgba(229, 235, 255, 0.8);
  line-height: 100px;
  margin: 0;
  font-weight: 100;
}
.bannerBtn {
  background-color: #243a9c;
  color: #ffffff;
}
.productList {
  max-width: 1200px;
  margin: auto;
}
.productListBox {
  margin: 50px 0;
}
.productListCard {
  margin: 0 50px;
  text-align: left;
}
</style>
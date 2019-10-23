<template>
  <div class="headerBar">
    <el-row class="header">
      <el-col :span="8">
        <div class="grid-content bg-purple" style="height:120px;">
          <img class="logo" src="../../assets/logo_white.svg" />
        </div>
      </el-col>
      <el-col :span="12" :offset="4">
        <div class="grid-content bg-purple-light">
          <el-row class="menu">
            <el-col :span="6">
              <div class="grid-content bg-purple">
                <el-dropdown @command="handleCommand">
                  <span class="el-dropdown-link menuList">
                    证书选购<i class="el-icon-arrow-down el-icon--right"></i>
                  </span>
                  <el-dropdown-menu slot="dropdown">
                    <el-dropdown-item command="a">黄金糕</el-dropdown-item>
                    <el-dropdown-item command="b">狮子头</el-dropdown-item>
                    <el-dropdown-item command="c">螺蛳粉</el-dropdown-item>
                    <el-dropdown-item command="d" disabled>双皮奶</el-dropdown-item>
                    <el-dropdown-item command="e" divided>蚵仔煎</el-dropdown-item>
                  </el-dropdown-menu>
                </el-dropdown>
              </div>
            </el-col>
            <el-col :span="6">
              <div class="grid-content bg-purple">帮助中心</div>
            </el-col>
            <el-col :span="6">
              <div class="grid-content bg-purple">关于我们</div>
            </el-col>
            <el-col :span="6">
              <div class="grid-content bg-purple">证书管理</div>
            </el-col>
          </el-row>
        </div>
      </el-col>
    </el-row>
  </div>
</template>
<script>
export default {
  methods: {}
};
</script>
<style >
.headerBar {
  background-image: linear-gradient(to right, #051146, #243a9c);
}
.header {
  height: 120px;
  max-width: 1200px;
  margin: auto;
}
.logo {
  height: 50px;
  margin: 35px 0;
}
.menu {
  color: #ffffff;
  line-height: 30px;
  font-size: 15px;
  margin: 45px 0;
}
.menuList{
  color: #ffffff;
  line-height: 30px;
  font-size: 15px;
  
}
</style>
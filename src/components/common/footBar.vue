<template>
  <div class="footBar">
    <el-row class="foot">
      <el-col :span="6">
        <div class="grid-content bg-purple">
          <div class="footList">x</div>
        </div>
      </el-col>
      <el-col :span="6" >
         <div class="grid-content bg-purple">
         <div class="footList">x</div>
        </div>
      </el-col>
      <el-col :span="6" >
         <div class="grid-content bg-purple">
          <div class="footList">x</div>
        </div>
      </el-col>
      <el-col :span="6" >
         <div class="grid-content bg-purple">
          <div class="footList">x</div>
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
.footBar {
  background-image: linear-gradient(to right, #051146, #243a9c);
}
.foot {
  height: 120px;
  max-width: 1200px;
  margin: auto;
}
.logo {
  height: 50px;
  margin: 35px 0;
}


.footList{
  background-color: #F6F6F6;
  height: 110px;
  margin: 10px;
}
</style>
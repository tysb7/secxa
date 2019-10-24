<template>
  <div class="footBar">
    <div class="foot">
       <el-row >
      <el-col :span="6">
        <div class="grid-content bg-purple">
          <div class="footList">
            <p class="footTitle">标准型DV SSL证书</p>
            <p class="footInfo">COMODO DV PositiveSSL SingleDomain</p>
            <p class="footInfo">COMODO DV PositiveSSL Multi-Domain</p>
            <p class="footInfo">COMODO DV PositiveSSL Wildcard SSL</p>
            <p class="footInfo">TRUSTOCEAN DV SecureSSL IP SSL</p>
          </div>
        </div>
      </el-col>
      <el-col :span="6" >
         <div class="grid-content bg-purple">
         <div class="footList">
            <p class="footTitle">企业型OV SSL证书</p>
            <p class="footInfo">COMODO OV Instant SSL</p>
            <p class="footInfo">COMODO OV Premium Wildcard SSL</p>
            <p class="footInfo">COMODO OV UCC SSL</p>
         </div>
        </div>
      </el-col>
      <el-col :span="6" >
         <div class="grid-content bg-purple">
          <div class="footList">
             <p class="footTitle">增强型EV SSL证书</p>
            <p class="footInfo">COMODO EV Positive Multi Domain SSL</p>
             <p class="footInfo">COMODO EV Positive Single Domain SSL</p>
              <p class="footInfo">TRUSTOCEAN EV Multi-Domain SSL</p>
               <p class="footInfo">TRUSTOCEAN EV SSL</p>
          </div>
        </div>
      </el-col>
      <el-col :span="6" >
         <div class="grid-content bg-purple">
          <div class="footList">
             <p class="footTitle">联系我们</p>
            <p class="footInfo">Phone:18091740360</p>
            <p class="footInfo">Sales:sales@secxa.com</p>
            <p class="footInfo">Support:support@secxa.com</p>
            <p class="footInfo">QQ:635308385 / 1159016159</p>
          </div>
        </div>
      </el-col>
    </el-row>
    <div style="height:100px;">
      <el-divider content-position="right"></el-divider>
      <p class="Copyright">Copyright © 2019 环智中诚SSL. All Rights Reserved. 陕ICP备16011250号-3</p>
    </div>
    </div>
   
    
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
 
  max-width: 1200px;
  margin: auto;
}
.logo {
  height: 50px;
  margin: 35px 0;
}


.footList{
  color: #ffffff;
  margin: 80px 10px;
  text-align: left;

}
.footTitle{
  font-size: 18px;
  line-height: 30px;
  margin-bottom: 30px;
  font-weight: 500;
}
.footInfo{
  color: rgba(229,235,255,.56);
  font-size: 14px;
  line-height: 25px;
}

.Copyright{
  color: #ffffff;
  text-align: left;
  font-size: 14px;
  line-height: 25px;
  
}
</style>
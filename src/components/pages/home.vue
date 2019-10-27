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
    <!-- <img src="../../assets/bgBottom.svg" alt=""> -->
    <!-- 主页banner -->
    <!-- productList -->
    <div class="productList">
      <h1>选购 HTTPS SSL 证书</h1>
      <h3>选择适合您的HTTPS SSL安全证书将会有助于提升您的网站服务器安全性和促进在线营销</h3>
      <el-row :gutter="12" class="productListBox">
        <el-col :span="8">
          <el-card shadow="hover" class="productListCard">
            <p class="productListBoxTitle">标准型DV SSL证书</p>
            <el-rate
              v-model="dvStars"
              disabled
              show-score
              :icon-classes="iconClasses"
              void-icon-class="el-icon-lock"
              text-color="#ff9900"
            ></el-rate>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>RSA & ECC双算法支持
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>超快速在线验证域名解析记录,快速签发
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>保护单条、多条或所有二级子域名，HTTPS域名
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>全球信任，通用性广，在线自主管理，不限制服务器安装次数
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>Linux、Mac、Windows、IOS、Android桌面和移动设备全球信任
            </p>

            <el-button icon="el-icon-lock" class="bannerBtn" style="margin-top:61px;">加入SSL</el-button>
          </el-card>
        </el-col>
        <el-col :span="8">
          <el-card shadow="hover" class="productListCard">
            <p class="productListBoxTitle">企业型OV SSL证书</p>
            <el-rate
              v-model="ovStars"
              disabled
              show-score
              :icon-classes="iconClasses"
              void-icon-class="el-icon-lock"
              text-color="#ff9900"
            ></el-rate>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>RSA & ECC双算法支持
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>支持展示中文或英文语言的企业信息
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>快速的国际OV企业身份认证
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>保护单条、多条或所有二级子域名，HTTPS域名
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>更好的兼容性保障，企业级安全性、可用性
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>获取工程师的全程认证和技术协助服务
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>Linux、Mac、Windows、IOS、Android桌面和移动设备全球信任
            </p>
            <el-button icon="el-icon-lock" class="bannerBtn">加入SSL</el-button>
          </el-card>
        </el-col>
        <el-col :span="8">
          <el-card shadow="hover" class="productListCard">
            <p class="productListBoxTitle">增强型EV SSL证书</p>
            <el-rate
              v-model="evStars"
              disabled
              show-score
              :icon-classes="iconClasses"
              void-icon-class="el-icon-lock"
              text-color="#ff9900"
            ></el-rate>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>RSA & ECC双算法支持
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>支持展示中文或英文语言的企业信息
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>严格的国际EV企业身份认证
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>地址栏展示企业名称或商标、对外贸易名称
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>保护单条、多条域名，EV HTTPS域名
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>获取工程师的全程认证和技术协助服务
            </p>
            <p class="productListBoxInfo">
              <i class="el-icon-lock lock"></i>Linux、Mac、Windows、IOS、Android桌面和移动设备全球信任
            </p>
            <el-button icon="el-icon-lock" class="bannerBtn">加入SSL</el-button>
          </el-card>
        </el-col>
      </el-row>
    </div>
    <!-- productList -->
    <!-- productList -->
    <div class="productList" style="margin-top:100px;">
      <h1>
        为什么选择环智中诚
        <span style="font-size: 15px;vertical-align: top;">®</span> SSL
      </h1>
      <h3>选择适合您的HTTPS SSL安全证书将会有助于提升您的网站服务器安全性和促进在线营销</h3>
      <el-row :gutter="20">
        <el-col :span="8">
          <div class="grid-content bg-purple" style="height:700px;">
            <div class="whyList">
              <div class="whyListBox">
                <i class="el-icon-s-check whyListicon"></i>
              </div>
              <div class="whyListTitle">全球顶级CA、可信颁发机构</div>
              <div
                class="whyListInfo"
              >环智中诚
        <span style="font-size: 15px;vertical-align: top;">®</span>同全球知名证书颁发机构Sectigo(COMODO CA)建立了深入的合作, 为您提供安全可信、兼容性最好的数字安全证书方案。Sectigo也是市场占有率最大的CA颁发机构。</div>
            </div>
             <div class="whyList">
              <div class="whyListBox">
                <i class="el-icon-s-platform whyListicon" style="margin-top: 10px;"></i>
              </div>
              <div class="whyListTitle">100%适配兼容</div>
              <div
                class="whyListInfo"
              >环智中诚
        <span style="font-size: 15px;vertical-align: top;">®</span>通过多个顶级根证书和中级根证书为您签发可在超过全球99%的流行的WEB浏览器和服务器上进行加密保护并完全兼容, 包含了PC桌面端设备、服务器端设备和移动端设备。</div>
            </div>
          </div>
        </el-col>
        <el-col :span="8">
          <div class="grid-content bg-purple">
           <span style="color:#fff">1</span>
            <img
              class="whyImg1"
              src="https://static.pgyer.com/static-20191022/images/newHome/homepage_tracup_middle_pic2.png"
              alt
            />
            <img
              class="whyImg2"
              src="https://static.pgyer.com/static-20191022/images/newHome/homepage_tracup_middle_pic1.png"
              alt
            />
          </div>
        </el-col>
        <el-col :span="8">
          <div class="grid-content bg-purple">
             <div class="whyList">
              <div class="whyListBox whyListBox_">
                <i class="el-icon-s-custom whyListicon"></i>
              </div>
              <div class="whyListTitle whyListTitle_">权威CA, 可信代理商</div>
              <div
                class="whyListInfo whyListInfo_"
              >依托COMODO CA的全球信任网络, 我们拥有绝对的价格优势和服务经验,旨在为您提供更加本地化，可靠的、可信的企业级数字证书服务。</div>
            </div>
             <div class="whyList">
              <div class="whyListBox whyListBox_">
                <i class="el-icon-s-comment whyListicon" style="margin-top: 10px;"></i>
              </div>
              <div class="whyListTitle whyListTitle_">一对一、专业的认证和技术顾问</div>
              <div
                class="whyListInfo whyListInfo_"
              >环智中诚™ 重视每一个客户的数字证书订单, 自您提交订单后，我们将会分配专人进行协助，从证书下单、支付到验证、安装，全程为您提供贴心的验证和技术支持。</div>
            </div>
          </div>
        </el-col>
      </el-row>
    </div>
    <!-- productList -->
    <!-- <three-bar></three-bar> -->
    <foot-bar></foot-bar>
  </div>
</template>
<script>
import headerBar from "@/components/common/HeaderBar";
import footBar from "@/components/common/FootBar";
// import threeBar from "@/components/common/ThreeBar";

export default {
  data() {
    return {
      dvStars: 4.1,
      ovStars: 4.8,
      evStars: 4.6
    };
  },
  methods: {},
  mounted() {},
  components: {
    headerBar,
    footBar
  }
};
</script>
<style scoped>
.banner {
  background-image: linear-gradient(to right, #051146, #243a9c);
  padding: 30px 0;
  
  /* padding: 50px 0; */
}
.bannertext {
  max-width: 1200px;
  margin: auto;
}
.bannerTitle {
  color: #ffffff;
  line-height: 100px;
  margin: 0;
  font-weight: 400;
}
.bannerInfo {
  color: rgba(229, 235, 255, 0.8);
  line-height: 30px;
  margin: 0;
  margin-bottom: 50px;
  font-weight: 400;
}
.bannerBtn {
  background-color: #243a9c;
  color: #ffffff;
  text-align: center;
  display: block;
  margin: 20px auto 20px;
  width: 120px;
  text-align: center;
  text-decoration: none;
}
.productList {
  max-width: 1200px;
  margin: 50px auto;
}
.productListBox {
  margin: 50px 0;
}
.productListCard {
  margin: 0 30px;
  text-align: left;
  min-height: 425px;
}
.productListBoxTitle {
  text-align: center;
  font-size: 17px;
}
.productListBoxInfo {
  font-size: 12px;
}
.whyImg1 {
  top: 60px;
  left: 50%;
  margin-left: -225px;
  width: 450px;
  height: 560px;
  position: absolute;
  box-shadow: none;
  border-radius: 0;
}
.whyImg2 {
  top: 110px;
  left: 50%;
  margin-left: -150px;
  width: 300px;
  height: 450px;
  position: absolute;
  box-shadow: none;
  border-radius: 0;
  animation: up-down 5s infinite;
}
@keyframes up-down {
  0% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-20px);
  }
  100% {
    transform: translateY(0);
  }
}
.whyListBox {
  border-radius: 50%;
  width: 54px;
  height: 54px;
  box-shadow: 0px 10px 30px 0px rgba(90, 118, 113, 0.12);
  background-color: #243a9c;
  float: right;
}
.whyListBox_{
  float: left;
}
.whyList {
  margin-top: 100px;
}
.whyListicon {
  font-size: 35px;
  color: #ffffff;
  margin-top: 8px;
}
.whyListTitle {
  padding-top: 70px;
  font-size: 20px;
  line-height: 1.6;
  text-align: right;
}
.whyListTitle_ {
 
  text-align: left;
}
.whyListInfo {
  color: #878f92;
  padding-top: 10px;
  text-align: right;
  font-size: 14px;
  line-height: 1.6;
}
.whyListInfo_ {
   text-align: left;
}
</style>
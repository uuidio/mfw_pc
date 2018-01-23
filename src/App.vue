<template>
  <!-- nav -->
  <div id="app">
      <div class="header">
      <div class="header-in">
          <div class="logo">
              <h1><a href="http://www.mafengwo.cn/mdd/" titile="蚂蜂窝自由行"></a></h1>
          </div>
          <div class="nav">
              <ul class="kone">
                  <li><router-link to="/index" active-class="active">首页</router-link></li>
                  <li><router-link to="/destination" active-class="active">目的地</router-link></li>
                  <li><router-link to="/strategy" active-class="active"><strong>NEW</strong>旅游攻略</router-link></li>
                  <li class="free"><router-link to="/shop" active-class="active">自由行商城</router-link></li>
                  <li><router-link to="/hotel" active-class="active">酒店</router-link></li>
                  <li><router-link to="/apple" active-class="active">APP</router-link></li>
              </ul>
          </div>
          <div class="activity"><a href=""><img src="./assets/img/act-euro2016.gif" width="64" height="42" alt="" /></a></div>
          <div class="lar">
              <a href=""></a>
              <a href=""></a>
              <a href=""></a>
              <a href="">登录</a>
              <a href="">|</a>
              <a href="">注册</a>
          </div>
      </div>
  </div>
  <div class="clear"></div>
  <!-- content -->
  <div class="clearfix">
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
  </div>
    <!-- footer -->
    <div class="footer">
      <div class="footer-in">
              <div class="footer-yi">
                  <dl>
                      <dt>中国领先的自由行服务平台</dt>
                      <dd>覆盖全球200多个国家和地区</dd>
                      <dd><strong>100,000,000</strong>位旅行者</dd>
                      <dd><strong>920,000</strong>家国际酒店</dd>
                      <dd><strong>21,000,000</strong>条真实点评</dd>
                      <dd><strong>382,000,000</strong>次攻略下载</dd>
                      <dd><a href=""><strong>中国旅游行业第一部“玩法”</strong></a></dd>
                  </dl>
                  <dl>
                      <dt>关于我们</dt>
                      <dd>
                      <a href="">关于蚂蜂窝</a>
                      <a href="">网络信息侵权通知指引</a>
                      <a href="">隐私政策</a>
                      <a href="">服务协议</a>
                      <a href="">联系我们</a>
                      <a href=""><strong>加入蚂蜂网</strong></a>
                      </dd>
                  </dl>
                  <dl>
                      <dt>旅行服务</dt>
                      <a href="">旅游攻略</a>
                      <a href="">旅游攻略</a>
                      <a href="">旅游攻略</a>
                      <a href="">旅游攻略</a>
                      <a href="">旅游攻略</a>
                      <a href="">旅游攻略</a>
                      <a href="">旅游攻略</a>
                      <a href="">旅游攻略</a>
                      <a href="">旅游攻略</a>
                      <a href="">旅游攻略</a>
                  </dl>
                  <div class="erweima">
                      <div class="first">
                          <span></span>
                          <span>马蜂窝官方微信</span>
                      </div>
                      <div class="second">
                          <span></span>
                          <span>马蜂窝良品</span>
                      </div>
                  </div>
              </div>
              <div class="footer-er">
                  <span>关注我们</span>
                  <div class="xh">
                      <a href=""><span></span></a>
                      <a href=""><span></span></a>
                      <a href=""><span></span></a>
                  </div>
              </div>
              <div class="footer-san">
                  <a href="">马可波罗</a>
                  <a href="">Onlylady女人志</a>
                  <a href="">艺龙旅游指南</a>
                  <a href="">欣欣旅游网</a>
                  <a href="">户外运动</a>
                  <a href="">365音乐网</a>
                  <a href="">百酷特色住宿</a>
                  <a href="">悠哉旅游网</a>
                  <a href="">小说网</a>
                  <a href="">来订吧酒店网</a>
                  <a href="">游多多自助游</a>
                  <a href="">教育</a>
                  <a href="">火车时刻表</a>
                  <a href="">驴妈妈旅游网</a>
                  <a href="">好豆美食网</a>
                  <a href="">二手车</a>
                  <a href="">绿野户外</a>
                  <a href="">途牛旅游网</a>
                  <a href="">图吧</a>
                  <a href="">SUV联合越野</a>
                  <a href="">手机浏览器</a>
                  <a href="">上海地图</a>
                  <a href="">天气预报查询</a>
                  <a href="">同程旅游</a>
                  <a href="">火车票</a>
                  <a href="">携程旅游</a>
                  <a href="">锦江旅游</a>
                  <a href="">火车时刻表</a>
                  <a href="">TripAdvisor</a>
                  <a href="">天巡网</a>
                  <a href="">自在客</a>
                  <a href="">租租车</a>
                  <a href="">五分旅游网</a>
                  <a href="">酒店预订</a>
                  <a href="">爱旅行网</a>
                  <a href="">旅游</a>
                  <a href="">旅游网</a>
                  <a href="">wed114结婚网</a>
                  <a href="">车讯网</a>
                  <a href="">遨游旅游网</a>
                  <a href="">手机</a>
                  <a href="">客运站</a>
                  <a href="">更多友情链接>></a>
              </div>
              <div class="footer-si">
                  <div class="z-logo"></div>
                  <div class="z-shuoming">
                      <p>全国统一客服电话：<span>4006-345-678</span>&nbsp;&nbsp;<a href="">网站地图</a></p>
                  </div>
                  <div class="z-cheng">
                      <a href=""><div class="xing"></div></a>
                      <a href=""><div class="ping"></div></a>
                  </div>
              </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style>
@charset "utf-8";
    body,div,dl,dt,dd,ul,ol,li,h1,h2,h3,h4,h5,h6,pre,form,fieldset,input,p,th,td {
    margin:0;
    padding:0;
}
body {
    font-size:12px;
    color:#3C3C3C;
}
fieldset,img {
    border:0;
}
ol,ul {
    list-style:none;
}
h1,h2,h3,h4,h5,h6 {
    font-size:100%;
}
em {
    font-style:normal;
}
button,select,textarea {
    outline:none;
}
input {
    border:0;
}
textarea {
    resize:none;
}
a {
    color:#333333;
    text-decoration:none;
}
a:hover {
    color:#ff9d00;
    text-decoration:none;
}
img {
    display:block;
    border:none;
}
.hot {
    color:#ff9d00 !important;
}
.clearfix:before,.clearfix:after {
    content:"";
    display:table;
}
.clearfix:after {
    clear:both;
}
.clearfix {
    *zoom:1;
}
.header{
    height:59px;
    border-bottom:1px solid #d6d6d6;
    box-sizing:border-box;
}
.header-in{
    width:1000px;
    height:58px;
    margin:0 auto;
    padding-top:13px;
    box-sizing:border-box;
}
/*logo*/
.logo{
    float:left;
    width:118px;
    height:32px;
    background:url(./assets/img/header-small-sprites.png) no-repeat;
}
/*nav*/
.nav{
    float:left;
    height:58px;
    margin-left:43px;
    margin-top:-13px;
}
.nav>ul{
    height:56px;
    line-height:56px;
}
.nav>ul>li{
    float:left;
    height:56px;
}
.nav>ul>li>a{
    height:56px;
    display:inline-block;
    padding:0 14px;
}
.nav strong{
    color:#ef523d;
    margin-right:4px;
}
.nav span{
    width:0;
    height:0;
    display:inline-block;
    border-width:4px;
    border-color:#666666 transparent transparent transparent;
    border-style:solid dashed dashed dashed;
    overflow:hidden;
    margin-left:3px;
    vertical-align:middle;
}
.nav>ul>li>a{
    height:59px;
    line-height:56px;
}
.xl{
    width:110px;
    border:1px solid #c9c9c9;
    border-top:0px;
    background-color:rgba(255,255,255,0.95);
    line-height:40px;
    position:absolute;
    z-index:999;
    display:none;
    margin-top:1px;
}
.xl li:hover{
    background:#efefef;
}
.xl li a:hover{
    color:#333333;
}
.xl li a{
    margin-left:16px;
}
.xlt{
    width:220px;
    border:1px solid #c9c9c9;
    border-top:0;
    background-color:rgba(255,255,255,0.95);
    line-height:40px;
    margin-top:-1px;
    position:absolute;
    z-index:999;
    display:none;
}
.xlt li a{
    margin-left:16px;
    margin-right:16px;
}
.zxlo{
    float:left;
    font-size:14px;
    line-height:65px;
}
.zxlt{
    float:right;}
.activity{
    float:left;
    margin-left:76px;
}
.lar{
    float:right;
}
.lar a{
    float:left;
    margin-left:9px;
    font-size:14px;
    color:#ff9d00;
    line-height:26px;
}
.lar a:nth-of-type(1){
    width:26px;
    height:26px;
    display:block;
    background:url(./assets/img/header-sprites11.png) 0 -50px no-repeat;
}
.lar a:nth-of-type(1):hover{
    background-position:0 -80px;
}
.lar a:nth-of-type(2){
    width:26px;
    height:26px;
    display:block;
    background:url(./assets/img/header-sprites11.png) -30px -50px no-repeat;
}
.lar a:nth-of-type(2):hover{
    background-position:-30px -80px;
}
.lar a:nth-of-type(3){
    width:26px;
    height:26px;
    display:block;
    background:url(./assets/img/header-sprites11.png) 0 -165px no-repeat;
}
.lar a:nth-of-type(3):hover{
    background-position:-30px -165px;
}
.lar a:nth-of-type(4):hover,.lar a:nth-of-type(6):hover{
    text-decoration:underline;
}
.lar a:nth-of-type(5){
    color:#c9c9c9;
}
/*banner*/
/*footer*/
.footer {
    background:#3c3c3c;
    margin-top:100px;
}
.footer-in {
    width:1000px;
    margin:0 auto;
    background:#3c3c3c;
    color:#c2c2c2;
    overflow:hidden;
}
.footer-yi {
    width:980px;
    height:167px;
    margin:0 auto;
    margin-top:24px;
}
.footer-yi dl {
    float:left;
}
.footer-yi dl dt {
    font-size:14px;
}
.footer-yi dl:nth-of-type(1) {
    width:168px;
}
.footer-yi dl:nth-of-type(1) dd {
    line-height:24px;
}
.footer-yi dl:nth-of-type(2) {
    width:120px;
    margin-left:100px;
}
.footer-yi dl:nth-of-type(2) a {
    display:block;
}
.footer-yi dl:nth-of-type(3) {
    text-align:center;
}
.footer-yi dl:nth-of-type(3) {
    width:132px;
    margin-left:100px;
}
.footer-yi dl:nth-of-type(3) a:nth-of-type(2),.footer-yi dl:nth-of-type(3) a:nth-of-type(4),.footer-yi dl:nth-of-type(3) a:nth-of-type(6),.footer-yi dl:nth-of-type(3) a:nth-of-type(8),.footer-yi dl:nth-of-type(3) a:nth-of-type(10) {
    padding-left:30px;
}
.footer-yi dl dd strong {
    font-weight:normal;
    color:#ff9d00;
}
.footer-in a {
    color:#c2c2c2;
    font-size:12px;
    line-height:24px;
}
.footer-in dl dd a:hover {
    color:#ffffff;
}
.erweima {
    float:right;
    width:220px;
    height:127px;
    margin-top:28px;
}
.first {
    float:left;
}
.first span:nth-of-type(1),.second span:nth-of-type(1) {
    width:90px;
    height:90px;
    display:block;
}
.first span:nth-of-type(1) {
    background:url(./assets/img/qr_mfw4.gif) no-repeat;
}
.second {
    float:right;
}
.second span:nth-of-type(1) {
    background:url(./assets/img/qr_tejia3.png) no-repeat;
}
.first span:nth-of-type(2),.second span:nth-of-type(2) {
    line-height:37px;
}
.erweima {
    float:right;
    width:220px;
    height:127px;
    margin-top:28px;
}
.first {
    float:left;
}
.first span:nth-of-type(1) {
    width:90px;
    height:90px;
    display:block;
    background:url(./assets/img/qr_mfw4.gif) no-repeat;
}
.second {
    float:right;
}
.second span:nth-of-type(1) {
    width:90px;
    height:90px;
    display:block;
    background:url(./assets/img/qr_tejia3.png) no-repeat;
}
.first span:nth-of-type(2),.second span:nth-of-type(2) {
    line-height:37px;
}
.footer-er {
    width:1000px;
    height:77px;
    text-align:center;
    margin-top:8px;
}
.footer-er span {
    line-height:49px;
}
.xh {
    width:114px;
    margin:0 auto;
}
.xh a:nth-of-type(1) span,.xh a:nth-of-type(2) span,.xh a:nth-of-type(3) span {
    float:left;
    width:28px;
    height:28px;
    display:block;
    background:url(./assets/img/mfw-footer-sprite4.png) no-repeat;
}
.xh a:nth-of-type(2) span,.xh a:nth-of-type(3) span {
    margin-left:15px;
}
.xh a:nth-of-type(2) span {
    background-position:-30px 0;
}
.xh a:nth-of-type(3) span {
    background-position:-60px 0;
}
.footer-san {
    width:980px;
    height:101px;
    border-top:1px solid #575a5b;
    margin:0 auto;
    margin-top:20px;
    padding:16px 0;
    box-sizing:border-box;
}
.footer-san a {
    display:inline-block;
    margin-right:8px;
}
.footer-si {
    width:1000px;
    height:88px;
    border-top:1px solid #575a5b;
    padding-top:14px;
    box-sizing:border-box;
}
.z-logo {
    float:left;
    width:136px;
    height:39px;
    display:block;
    background:url(./assets/img/mfw-footer-sprite4.png) no-repeat 0 -30px;
}
.z-shuoming {
    float:left;
    margin-left:20px;
}
.z-shuoming p span {
    color:#ff9d00;
}
.z-shuoming p a {
    color:#ff9d00;
}
.z-shuoming p a:hover {
    color:#ff9d00;
}
.z-cheng {
    float:right;
    width:190px;
    height:39px;
}
.xing {
    float:left;
    width:90px;
    height:39px;
    background:url(./assets/img/mfw-footer-sprite4.png) no-repeat 0px -69px;
}
.ping {
    float:right;
    width:90px;
    height:39px;
    background:url(./assets/img/mfw-footer-sprite4.png) no-repeat 0 -110px;
}
.kone li a.active{
  background: #ff9e00;
  color: #fff;
}

</style>

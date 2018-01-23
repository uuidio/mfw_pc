<template>
  <div>
<div class="wrap">
    <div class="main-wrap">
        <div class="main-left">
            <div class="banner">
                        <div class="shaomiao">
                                 <div class="shouji ">
                                        <div class="shouji-in">
                                            <ul>
                                                            <li><img src="../../assets/img/2016-6-1.png" alt="" /></li>
                                                            <li><img src="../../assets/img/2016-6-2.png" alt="" /></li>
                                                            <li><img src="../../assets/img/2016-6-3.png" alt="" /></li>
                                                            <li><img src="../../assets/img/2016-6-4.png" alt="" /></li>
                                                            <li><img src="../../assets/img/2016-6-5.png" alt="" /></li>
                                            </ul>
                                        </div>
                                </div>
                                <div class="xiamian">
                                    <ol>
                                            <li class="current"></li>
                                            <li></li>
                                            <li></li>
                                            <li></li>
                                            <li></li>
                                    </ol>
                                    <div class="app"></div>
                                </div>
                        </div>
            </div>
                <div class="download">
                        <div>
                            <ul>
                                <li><a href=""></a></li>
                                <li><a href=""></a></li>
                                <li><a href=""></a></li>
                                <li><a href=""></a></li>
                            </ul>
                        </div>
                        <dl>
                            <dt>全球旅游攻略首选，1亿用户信赖，旅行必备</dt>
                            <dd>-超值特卖：机票+酒店、当地游、门票、签证、保险等一应俱全，省钱省心</dd>
                            <dd>-超值特卖：机票+酒店、当地游、门票、签证、保险等一应俱全，省钱省心</dd>
                            <dd>-超值特卖：机票+酒店、当地游、门票、签证、保险等一应俱全，省钱省心</dd>
                            <dd>-超值特卖：机票+酒店、当地游、门票、签证、保险等一应俱全，省钱省心</dd>
                            <dd>-超值特卖：机票+酒店、当地游、门票、签证、保险等一应俱全，省钱省心</dd>
                        </dl>
                </div>
        </div>
        <div class="main-right">
            <ul>
                <li><a href=""></a><img src="../../assets/img/logo_gonglve_v6.png" alt="" /></li>
                <li><a href=""></a><img src="../../assets/img/logo_fanyi2.png" alt="" /></li>
                <li><a href=""></a><img src="../../assets/img/logo_wengweng50.png" alt="" /></li>
            </ul>
        </div>
    </div>
</div>
  </div>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  /*main*/
.wrap {
    width:980px;
    height:754px;
    margin:30px auto;
    overflow:hidden;
    position:relative;
}
/*banner*/
.banner {
    float:left;
    width:850px;
    height:407px;
    border-radius:10px;
    background:url(../../assets/img/bn_bg2.jpg) repeat;
    position:relative;
}
.shaomiao {
    width:204px;
    height:600px;
    position:absolute;
    top:85px;
    left:34px;
    overflow:hidden;
    transition:all 1s;
}
.shouji {
    width:204px;
    height:425px;
    background:url(../../assets/img/app_n_sprite5.gif) no-repeat 0 0;
    overflow:hidden;
}
.shouji-in {
    width:170px;
    height:302px;
    background:#000;
    margin:63px auto;
    position:relative;
    overflow:hidden;
}
.shouji-in ul {
    width:2000px;
    position:absolute;
    left:0;
}
.shouji-in ul li {
    float:left;
}
ol {
    position:absolute;
    left:30%;
    margin-left:-34px;
    bottom:130px;
}
ol li {
    float:left;
    width:11px;
    height:11px;
    background:#bdbcbd;
    border-radius:50%;
    margin-left:5px;
    cursor:pointer;
}
.current {
    background:#ffa800;
}
.app {
    width:100px;
    height:100px;
    background:url(../../assets/img/logo_gonglve_v6.png) no-repeat;
    margin:70px auto;
}
.download {
    float:right;
    width:588px;
    height:268px;
    margin-right:130px;
    margin-top:26px;
}
.download div ul {
    height:42px;
    margin-bottom:46px;
}
.download div ul li {
    float:left;
    width:124px;
    height:42px;
    background:#000;
    background:url(../../assets/img/app_n_sprite5.gif) no-repeat 0 0;
    margin-right:20px;
}
.download li:nth-of-type(1) {
    background-position:-225px 0;
}
.download li:nth-of-type(1):hover {
    background-position:-225px -64px;
}
.download li:nth-of-type(2) {
    background-position:-385px 0;
}
.download li:nth-of-type(2):hover {
    background-position:-385px -64px;
}
.download li:nth-of-type(3) {
    background-position:-545px 0;
}
.download li:nth-of-type(3):hover {
    background-position:-545px -64px;
}
.download li:nth-of-type(4) {
    width:156px;
    height:42px;
    margin:0;
    background-position:-705px 0;
}
.download li:nth-of-type(4):hover {
    background-position:-705px -64px;
}
.download dt {
    padding-bottom:12px;
    font-size:22px;
    font-weight:bold;
    line-height:30px;
}
.download dd {
    font-size:14px;
    color:#666;
    line-height:28px;
}
.main-right {
    float:right;
    width:110px;
    height:407px;
    position:absolute;
    right:0px;
    top:0px;
}
.main-right  li:nth-of-type(1) {
    width:105px;
    height:88px;
    background:url(../../assets/img/app_n_sprite5.gif) no-repeat -225px -163px;
    overflow:hidden;
}
.main-right  li:nth-of-type(1) img {
    margin:9px 0 0 26px;
}
.main-right  li:nth-of-type(2) img {
    margin:9px 0 0 26px;
}
.main-right  li:nth-of-type(3) img {
    margin:9px 0 0 26px;
}
</style>

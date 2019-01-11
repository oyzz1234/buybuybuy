<template>
  <div id="app">
    <div class="header">
      <!-- 1.0 导航栏头部 -->
      <div class="head-top">
        <div class="section">
          <div class="left-box">
            <span>黑马买买买</span>
            <a
              target="_blank"
              href="#"
            ></a>
            <a
              target="_blank"
              href="#"
            ></a>
          </div>
          <div
            id="menu"
            class="right-box"
          >
            <span style="display: none;">
              <a
                href=""
                class=""
              >登录</a>
              <strong>|</strong>
              <a
                href=""
                class=""
              >注册</a>
              <strong>|</strong>
            </span>
            <span>
              <a
                href=""
                class=""
              >会员中心</a>
              <strong>|</strong>
              <a>退出</a>
              <strong>|</strong>
            </span>
            <a
              href=""
              class=""
            >
              <i class="iconfont icon-cart"></i>购物车(
              <span id="shoppingCartCount">
                <span>4</span>
              </span>)</a>
          </div>
        </div>
      </div>
    </div>
    <div class="footer">
      <div class="section">
        <div class="foot-nav">
          <a href="">关于我们</a>
          <strong>|</strong>
          <a href="">联系我们</a>
          <strong>|</strong>
          <a href="">联系客服</a>
          <strong>|</strong>
          <a href="">合作招商</a>
          <strong>|</strong>
          <a href="">商家帮助</a>
          <strong>|</strong>
          <a href="">营销中心</a>
          <strong>|</strong>
          <a href="">隐私政策</a>
        </div>
        <div class="foot-box">
          <div class="copyright">
            <p>版权所有 黑马买买买 </p>
            <p>公司地址： 联系电话：</p>
            <p class="gray">Copyright © 2009-2018 itcast Corporation,All Rights Reserved.</p>
          </div>
          <div class="service">
            <p>周一至周日 9:00-24:00</p>
            <a href="#">
              <i class="iconfont icon-phone"></i>在线客服</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>


export default {
 name: "blackvue"
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
  <div id="index">
    <div class="header">
      <div class="header1">
        <div class="avatar">
          <img src="../image/header.png" alt="">
        </div>
        <div class="introduction">
          <ul>
            <li>
              <div>
                <img src="../image/brand@3x.png" alt="">
              </div>
              <h2>粥品香坊（回龙观）</h2>
            </li>
            <li>
              <p>蜂鸟专送</p>
            </li>
            <li>
              <img src="../image/decrease_1@3x.png" alt="">
              <p class="annotated">在线支付满28减5</p>
              <p>5个<span>&gt;</span></p>
            </li>
          </ul>
        </div>
      </div>
      <div class="announcement">
        <img src="../image/bulletin@3x.png" alt="">
        <p>粥品香坊其烹饪粥料的秘方源于中国千年古法，在融和现代制作工艺，由世界烹饪大师屈浩先生领衔研发。坚守纯天然、0添加的良心品质深得消费者青睐，发展至今成为粥类的引领品牌。是2008年奥运会和2013年园博会指定餐饮服务商。

        </p>
        <span>&gt;</span>
      </div>
    </div>
    <div class="nav">
      <ul>
        <li>商品</li>
        <li>评价</li>
        <li>商家</li>
      </ul>
    </div>
    <div class="content">
      <div class="side">
        <ul>
          <li>
            <p>热销榜</p></li>
          <li>
            <p>
              <img src="../image/special_3@2x.png" alt="">
              单人特色套餐
            </p>
          </li>
          <li><p>特色粥品</p></li>
          <li><p>精选热菜</p></li>
          <li><p>爽口凉菜</p></li>
          <li><p>办成品</p></li>
          <li><p>饭类</p></li>
          <li><p>面类</p></li>
          <li><p>特色粥品</p></li>
        </ul>
      </div>
      <div class="sidec">
        <p class="title">单人特色套餐</p>
        <div class="wrap">
          <img src="../image/foot.png" alt="">
          <ul>
            <li>
              <h2>皮蛋瘦肉粥配包子套餐</h2>
            </li>
            <li>
              <p>咸粥</p>
            </li>
            <li>
              <p>月销1132份<span>好评率100%</span></p>
            </li>
            <li>
              <p>￥24</p>
              <p>￥28</p>
              <p>+</p>
            </li>
          </ul>
        </div>
        <p class="title">单人特色套餐</p>
        <div class="wrap1">
          <div>
            <img src="../image/foot.png" alt="">
            <ul>
              <li>
                <h2>皮蛋瘦肉粥配包子套餐</h2>
              </li>
              <li>
                <p>咸粥</p>
              </li>
              <li>
                <p>月销1132份<span>好评率100%</span></p>
              </li>
              <li>
                <p>￥24</p>
                <p>￥28</p>
                <p>+</p>
              </li>
            </ul>
          </div>
        </div>
        <div class="wrap1">
          <div>
            <img src="../image/foot.png" alt="">
            <ul>
              <li>
                <h2>皮蛋瘦肉粥配包子套餐</h2>
              </li>
              <li>
                <p>咸粥</p>
              </li>
              <li>
                <p>月销1132份<span>好评率100%</span></p>
              </li>
              <li>
                <p>￥24</p>
                <p>￥28</p>
                <p>+</p>
              </li>
            </ul>
          </div>
        </div>
        <div class="wrap1">
          <div>
            <img src="../image/foot.png" alt="">
            <ul>
              <li>
                <h2>皮蛋瘦肉粥配包子套餐</h2>
              </li>
              <li>
                <p>咸粥</p>
              </li>
              <li>
                <p>月销1132份<span>好评率100%</span></p>
              </li>
              <li>
                <p>￥24</p>
                <p>￥28</p>
                <p>+</p>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  window.addEventListener('orientationchange', setRem)
  window.addEventListener('resize', setRem)
  setRem()
  function setRem () {
    let html = document.querySelector('html')
    let width = html.getBoundingClientRect().width
    html.style.fontSize = width / 16 + 'px'
  };
  export default {
    name: 'hello',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import "../css/reset.css";
  @import "../css/index";
</style>

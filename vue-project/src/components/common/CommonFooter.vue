<template>
  <div class="footer">
    <ul>
      <li>电影</li>
      <li>音乐</li>
      <li>书籍</li>
      <li>图片</li>
    </ul>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    /*@import "../../assets/css/reset.css";*/
    .footer{
      height: 1rem;
      background: rgb(33,150,243);
      color: #fff;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    .footer ul{
      display: flex;
      
    }
    .footer ul li{
      flex: 1;
      text-align: center;
      height: 1rem;
      line-height: 1rem;
      /*font-size: 14px;*/
    }
</style>

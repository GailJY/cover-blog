<template>
  <div class="header" >
    <div class="main">
      <div class="main_inner inverted">
          <div class="main_content">
            <div class="item_circle item_right">
              <a href="" title="前往 叶嘉宇 的主页">
              <div class="img">
                <img src="../assets/avatar.jpg">
              </div>
              <div class="info">
                <div class="info-back">
                  <h2>{{name}}</h2>
                  <p>{{info}}</p>
                </div>
              </div>
              </a>
            </div>
          <!-- 头像 -->  
            <h1 class="cover_title">{{msg}}</h1>
            <span class="cover_subtitle">个人站</span>
            <hr class="cover_divider">
            <p class="cover_description">欢迎来到我的个人网站~</p>
            <hr class="cover_divider cover_divider-second">
            <div>
              <nav class="cover-navigations">
                <ul class="navigations">
                  <li class="navigation_item"><router-link to="/">博客主页</router-link></li>
                  <li class="navigation_item"><router-link to="/about"
                  >所有文章</router-link></li>
                  <li class="navigation_item"><router-link to="">标签</router-link></li>
                  <li class="navigation_item"><router-link to="">技术支持</router-link></li>
                  <li class="navigation_item"><router-link to="">关于我</router-link></li>
                </ul>
              </nav>
            </div>
          </div>
      </div>


    </div>

    <div class="cover-overlay"></div>

  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
    name: String,
    info: String
  },
  data() {
    return{
      cover_arr:['博客主页','所有文章','标签','技术支持','关于我'],
    }  
  },
  methods:{
    routerChange: function(to, from){
      console.log(to.path)
      console.log(from.path)
    }
  },
  
};

</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
$img:'../assets/';
@import "../assets/css/1.scss";

ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #666666;
}
</style>

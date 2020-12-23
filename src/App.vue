<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view />
    
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin:0;
  padding:0;
  border:0;
  font-size:100%;
  font:inherit;
  vertical-align:baseline;
}
html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary, time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline; }
body{
  width: 100%;
  *zoom: 1; 
  margin:0;
  font-size:14px;
  line-height:1;
}
body:before, body:after {
  content: "";
  display: table; 
}
hr{
  border:0;
}
a{
  text-decoration:none;
}
h1,
h2,
h3,
h4,
h5,
h5 {
    margin-top: 1.0em;
    margin-bottom: .5em;
    font-family: "ff-tisa-web-pro-1", "ff-tisa-web-pro-2", "Lucida Grande", "Hiragino Sans GB", "Hiragino Sans GB W3", "Microsoft YaHei", "WenQuanYi Micro Hei", sans-serif;
    font-weight: lighter;
    color: #333333;
    -webkit-font-smoothing: antialiased; 
  }
ol li, ul li{
  margin: 0 0 .2em 0;
  line-height:1.6em;
}
</style>

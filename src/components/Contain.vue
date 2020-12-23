<template>
    <div class="contain-wrap">
        <div class="contain_inner">
            <div class="contain_inner">
                <article>
                    <header class="post-header">
                        <h1 class="post-title">文章</h1>
                    </header>
                    <section>
                        <div>
                            <div>
                                <h3>2020</h3>
                            </div>
                            <div class="post-list">
                                <ul>
                                    <li>
                                        <span>2020-07-11</span> » 
                                        <a href="">博客开发</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </section>
                </article>
                <section class="footer">
                    <div class="footer-div">
                        <nav class="cover-navigation">
                            <ul class="navigation">
                                <li class="nav_item">
                                    <a href="">
                                        <div class="footer-icon"></div>
                                    </a>
                                </li>
                                <li class="nav_item">
                                    <a href="">
                                        <div class="footer-icon" style="background:url(../assets/email.png)"></div>
                                    </a>
                                </li>
                                <li class="nav_item">
                                    <a href="">
                                        <div class="footer-icon" style="background:url(../assets/email.png)"></div>
                                    </a>
                                </li>
                                <li class="nav_item">
                                    <a href="">
                                        <div class="footer-icon" style="background:url(../assets/email.png)"></div>
                                    </a>
                                </li>
                            </ul>
                        </nav>
                    </div>
                </section>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Contain",
    data() {
        return{
            icon:require('../assets/email.png')
        }
    }   
}
</script>

<style lang="scss">
$img:'../';
@import "../assets/css/contain.scss";
h1{
  margin-top: 0;
  font-size: 1.5em;
  line-height: 1.2em;
  letter-spacing: .05em; 
  font-weight: bold;
}
</style>
<template>
    <div class="app">
        <div class="app-wrapper">
            <div class="home-page">
                <header class="header">
                    <div class="header-row">
                        <div class="header-left">
                            <img src="./images/tbd100100.png" width="80" height="80" alt="CN-RUS-OnlineShopping"
                                class="image-title">
                            <!-- <img src="./images/tbd.png" alt="CN-RUS-OnlineShopping" class="image-titletext"> -->
                            <h1>CN-RUS-OnlineShopping</h1>
                        </div>
                        <div class="header-right">
                            <ul role="menu">
                                <li>
                                    <a href="http://www.baidu.com" title="Link1" target="_blank">
                                        Link1
                                    </a>
                                </li>
                                <li>
                                    <a href="http://www.bing.com" title="Link2" target="_blank">
                                        Link2
                                    </a>
                                </li>
                                <li>
                                    <a href="http://www.bilibili.com" title="Link3" target="_blank">
                                        Link3
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </header>
                <div class="container">
                    <div class="slogan-con">
                        <div class="slogan">
                            Slogan.
                        </div>
                    </div>
                </div>
                <div class="template-wrapper">
                    <div class="backdrop">
                        <div class="road">
                            <div class="lane"></div>
                        </div>
                        <div class="overlay1"></div>
                        <div class="overlay2"></div>
                    </div>
                    <div class="template-con">
                        <div class="template-intro">
                            <div class="template-title">
                                Title
                            </div>
                            <div class="template-subtitle">
                                Subtitle
                            </div>
                        </div>
                    </div>
                </div>
                <footer>
                    <div class="footer-wrapper">
                        <section class="footer-nav">
                            <ul class="contact-us">
                                <li>Contact Us</li>
                                <li class="mail-link">
                                    <a href="mailto:1946029982@qq.com">
                                        mailto@xxx.com
                                    </a>
                                </li>
                                <li class="icons">
                                    <span class="icon-tooltip wechat-icon">
                                        <i class="icon iconfont iconweixin">
                                            &#xe600;
                                        </i>
                                        <span class="code-img">
                                            <img src="./images/tbd200200.png">
                                        </span>
                                    </span>

                                    <span class="icon-tooltip zhihu-icon">
                                        <a href="https://www.zhihu.com" target="_blank">
                                            <i class="icon iconfont iconzhihu">
                                                &#xf276;
                                            </i>
                                        </a>
                                    </span>
                                </li>
                            </ul>
                        </section>
                    </div>
                </footer>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'OnlineShopping',
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import "./OnlineShopping.css";
</style>

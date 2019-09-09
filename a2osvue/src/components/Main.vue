<template>
  <div id="main">
    <div class="inner">
      <!-- Header -->
      <header id="header">
        <a href="index.html" class="logo">
          <strong>A2OS</strong> 南京航空航天大学开源社区
        </a>
        <ul class="icons">
          <li>
            <a href="https://github.com/NUAA-Open-Source" class="icon fa-github">
              <span class="label">Github</span>
            </a>
          </li>
          <li>
            <a href="https://t.me/NUAAOpenSource" class="icon fa-telegram">
              <span class="label">Telegram</span>
            </a>
          </li>
          <li>
            <a href="mailto:a2os-general@googlegroups.com" class="icon fa-envelope">
              <span class="label">Email</span>
            </a>
          </li>
        </ul>
      </header>

      <!-- Banner -->
      <section id="banner">
        <div class="content">
          <header>
            <h1>A2OS</h1>
            <h2>
              NUAA Open Source
              <br />南京航空航天大学开源社区
            </h2>
            <p>助力每一个南航人成就非凡</p>
          </header>
          <ul class="actions">
            <li>
              <a href="#" class="button big">了解更多</a>
            </li>
          </ul>
        </div>
      </section>

      <!-- Section -->
      <section>
        <header class="major">
          <h2>A2OS 资源概览</h2>
        </header>
        <div class="row">
          <div class="col-12">
            <p></p>
          </div>
        </div>
        <div class="row">
          <div class="col-12">
            <a href="https://safeu.a2os.club" class="button big">SafeU</a>
            <p style="display: inline; margin-left: 20px">安全、快速的文件分享渠道</p>
          </div>
        </div>
        <br />
        <div class="row">
          <div class="col-12">
            <a href="https://blogroll.a2os.club" class="button big">Blogroll</a>
            <p style="display: inline; margin-left: 20px">南京航空航天大学 Blog 收集计划</p>
          </div>
        </div>
        <br />
        <div class="row">
          <div class="col-12">
            <a href="#weekly" class="button big">Weekly</a>
            <p style="display: inline; margin-left: 20px">周常培训</p>
          </div>
        </div>
      </section>
      <!-- Section -->

      <!-- Section -->
      <section>
        <header class="major">
          <h2>A2OS Weekly</h2>
        </header>
        <div class="row" id="weekly">
          <div class="col-12">
            <p>
              有道无术，术尚可求，有术无道，止于术。
              <br />如果说网络安全是互联网发展的“道”，漏洞则是互联网安全的“术”。要谈网络安全，必须说清楚漏洞。若只谈漏洞，则不知言之所谓。
              <br />本次分享从漏洞入手，讲解部分基础的Web安全知识。
              <br />时间：3 月 30 日（周六）晚 19:30 - 21:00
              <br />地点：江宁校区一号楼六楼IT创新区会议室
              <br />讲者：陆建宇
            </p>
          </div>
        </div>
        <div class="row">
          <div class="col-12">
            <a href="https://groups.google.com/group/a2os-general" class="button big">
              关注邮件列表及时获取 A2OS
              Weekly 的消息
            </a>
            <a
              href="https://github.com/NUAA-Open-Source/A2OS/blob/master/历次培训及讲座.md"
              class="button big"
            >查看历届 A2OS Weekly</a>
          </div>
        </div>
      </section>
      <!-- Section -->

      <!-- Section -->
      <section>
        <header class="major">
          <h2>Members</h2>
        </header>
        <div class="row">
          <div class="col-12">
            <div class="row gtr-uniform" id="members">
              <a href="https://github.com/40m41h42t">
                <img class="icon avatar" src="images/40m41h42t.png" alt />
              </a>
              <a href="https://github.com/arcosx">
                <img class="icon avatar" src="images/arcosx.png" alt />
              </a>
              <a href="https://github.com/LogicJake">
                <img class="icon avatar" src="images/logicjake.png" alt />
              </a>
              <a href="https://github.com/milkice233">
                <img class="icon avatar" src="images/milkice.png" alt />
              </a>
              <a href="https://github.com/RayZhao1998">
                <img class="icon avatar" src="images/ninjiacoder.png" alt />
              </a>
              <a href="https://github.com/RyanSu98">
                <img class="icon avatar" src="images/RyanSu.png" alt />
              </a>
              <a href="https://github.com/seiry">
                <img class="icon avatar" src="images/seiryyu.png" alt />
              </a>
              <a href="https://github.com/Triple-Z">
                <img class="icon avatar" src="images/triplez.png" alt />
              </a>
              <a href="https://github.com/Villivateur">
                <img class="icon avatar" src="images/vvzero.png" alt />
              </a>
              <a href="https://github.com/ZeddYu">
                <img class="icon avatar" src="images/ZeddYu.png" alt />
              </a>
            </div>
          </div>
        </div>
        <br />
        <div class="row">
          <div class="col-12">
            <a
              href="https://github.com/NUAA-Open-Source/"
              class="button big"
            >加入我们的 GitHub 组织，你将会出现在这里。</a>
          </div>
        </div>
      </section>
      <!-- Section -->
    </div>
    <div style="text-align: center">
      <hr />
      <a class="beianhao" href="http://www.miitbeian.gov.cn/">苏ICP备17037222-4号</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Main",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

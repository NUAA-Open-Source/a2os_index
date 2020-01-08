<template>
  <div id="main">
    <div class="inner">
      <!-- Header -->
      <header id="header">
        <router-link to="/"  class="logo"><strong>A2OS</strong> 南京航空航天大学开源社区</router-link>
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
            <a href="https://guide.a2os.club" class="button big">A2OS Guide</a>
            <p style="display: inline; margin-left: 20px">存放了南航非官方组织或个人开发的各类产品或小制作</p>
          </div>
        </div>
        <br />
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
              各位同学：
              <br />经历了一个暑假，A2OS 的 Weekly 又开始了，本周由我给大家带来的主题是《我是如何从0到1参与 Swift 的开发》。
              <br /> 我第一次冒出参与 Swift 编译器的开发是从 Swift Forum 上的一个帖子开始的，<a href="https://forums.swift.org/t/what-should-i-learn-if-i-want-to-contribute-to-the-swift-compiler/18144">如果我想给 Swift 编译器贡献代码我该学习什么？</a>在这个帖子里面，很多人给出了如何学习编译器。
              <br />在我前往美国圣何塞参加了 WWDC 听 What‘s new in Swift 的时候，发现有一个新特性是一个高中生提出并完成开发的，那是我坚定了尝试参与 Swift Compiler 开发。
              <br />于是利用周末的时间选择了 Swift 的一个 Starter bug 并修复了它，整个过程还是相当有趣的。
              <strong>
                <br /><br />时间：2019.11.9 晚上 7:30 - 8:30
                <br />地点：将军路校区一号楼6楼学生IT创新创业区会议室
                <br />讲者：赵子渊
              </strong>
            </p>
          </div>
        </div>
        <div class="row">
          <div class="col-12">
            <a href="https://groups.google.com/group/a2os-general" class="button big" style="margin-right: 5px" target="_blank">
              关注邮件列表及时获取 A2OS
              Weekly 的消息
            </a>
            <a
              href="https://github.com/NUAA-Open-Source/A2OS/blob/master/历次培训及讲座.md"
              class="button big"
              target="_blank"
            >查看历届 A2OS Weekly</a>
          </div>
        </div>
      </section>
      <!-- Section -->

      <Member />
    </div>
    <div style="text-align: center">
      <hr />
      <a class="beianhao" href="http://www.miitbeian.gov.cn/">苏ICP备17037222-4号</a>
    </div>
  </div>
</template>

<script>
import Member from './Member'
export default {
  name: "Main",
  props: {},
  components: {
    Member
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.avatar {
  width: 5em;
  height: 5em;
  border-radius: 5em;
}

h3 img {
  height: 1em;
}

#members a {
  border-bottom: none;
}


</style>

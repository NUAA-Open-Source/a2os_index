<template>
  <section>
    <header class="major">
      <h2>Sponsors</h2>
    </header>
    <div class="row">
      <div class="col-12">
        <div class="row gtr-uniform" id="members">
          <a v-for="s of sponsors" :key="s.link" :href="s.link">
            <img class="icon avatar" :src="s.avatar" alt="" />
          </a>
        </div>
      </div>
    </div>
    <br />
    <div class="row">
      <div class="col-12 sponsor">
        <span
          href="https://github.com/NUAA-Open-Source/"
          class="button big"
          target="_blank"
          @mouseover="toggleQRCodeShow()"
          @mouseout="toggleQRCodeShow()"
          >赞助我们，资金将用于服务器租赁、域名续费等</span
        >
        <div v-show="qrcodeIsShow" class="sponsor-info">
          <img :src="require('../../public/img/IMG_2543.jpg')" class="qrcode" />
          <span>支付宝</span>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Sponsor",
  props: {},
  methods: {
    toggleQRCodeShow: function() {
      this.qrcodeIsShow = !this.qrcodeIsShow;
    }
  },
  data() {
    return {
      qrcodeIsShow: false,
      sponsors: [
        {
          link: "https://github.com/arcosx",
          avatar: "https://avatars3.githubusercontent.com/u/17517365?s=460&v=4"
        },
        {
          link: "https://github.com/RayZhao1998",
          avatar: "https://avatars0.githubusercontent.com/u/22616933?s=460&v=4"
        },
        {
          link: "https://github.com/Villivateur",
          avatar: "https://avatars3.githubusercontent.com/u/30222160?s=460&v=4"
        },
        {
          link: "https://github.com/Muyun99",
          avatar: "https://avatars0.githubusercontent.com/u/27944418?s=460&v=4"
        }
      ]
    };
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

.hover-image img {
  display: none;
}

.hover-image:hover img {
  display: block;
}

.sponsor {
  position: relative;
}

.sponsor-info {
  position: absolute;
  display: flex;
  flex-direction: column;
  align-items: center;
  top: -12em;
}

.qrcode {
  width: 10em;
  height: 10em;
}
</style>

<template>
  <section>
    <header class="major">
      <h2>Members</h2>
    </header>
    <div class="row">
      <div class="col-12">
        <div class="row gtr-uniform" id="members">
          <a v-for="m of members" :key="m.link" :href="m.link">
            <!-- {{m}} -->
            <img class="icon avatar" :src="m.avatar" alt="" />
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
          target="_blank"
        >加入我们的 GitHub 组织，你将会出现在这里。</a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Member",
  props: {},
  data() {
    return {
      members: [
        {
          link: "https://github.com/40m41h42t",
          avatar: "https://avatars2.githubusercontent.com/u/43204230?s=460&v=4"
        },

        {
          link: "https://github.com/arcosx",
          avatar: "https://avatars3.githubusercontent.com/u/17517365?s=460&v=4"
        },

        {
          link: "https://github.com/LogicJake",
          avatar: "https://avatars3.githubusercontent.com/u/20673460?s=460&v=4"
        },

        {
          link: "https://github.com/milkice233",
          avatar: "https://avatars0.githubusercontent.com/u/5274559?s=460&v=4"
        },

        {
          link: "https://github.com/RayZhao1998",
          avatar: "https://avatars0.githubusercontent.com/u/22616933?s=460&v=4"
        },

        {
          link: "https://github.com/RyanSu98",
          avatar: "https://avatars0.githubusercontent.com/u/33794423?s=460&v=4"
        },

        {
          link: "https://github.com/seiry",
          avatar: "https://avatars2.githubusercontent.com/u/4397354?s=460&v=4"
        },

        {
          link: "https://github.com/Triple-Z",
          avatar: "https://avatars3.githubusercontent.com/u/16285716?s=460&v=4"
        },

        {
          link: "https://github.com/Villivateur",
          avatar: "https://avatars3.githubusercontent.com/u/30222160?s=460&v=4"
        },

        {
          link: "https://github.com/ZeddYu",
          avatar: "https://avatars3.githubusercontent.com/u/29536474?s=460&v=4"
        },
        {
          link: "https://github.com/Kit4y",
          avatar: "https://avatars0.githubusercontent.com/u/38547290?s=460&v=4"
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
</style>

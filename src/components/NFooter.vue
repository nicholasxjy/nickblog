<template>
  <footer class="footer">
    <div class="group">
      <div class="group-title">
        SOCIAL
      </div>
      <div class="group-link">
        <a href="https://twitter.com/Normal_Geek_Xue">Twitter</a>
        <a href="https://www.facebook.com/a.chef.salad">Facebook</a>
        <a href="https://www.instagram.com/nicholas_xue">Instagram</a>
      </div>
    </div>
    <div class="group">
      <div class="group-title">
        COOL
      </div>
      <div class="group-link">
        <router-link :to="{name: 'nmusic'}">Music</router-link>
        <router-link :to="{name: 'nvideo'}">Video</router-link>
      </div>
    </div>
    <div class="group">
      <div class="group-title">
        CONTCAT
      </div>
      <div class="group-link">
        <a href="https://github.com/nicholasxjy">Github</a>
      </div>
    </div>
  </footer>
</template>

<script>
  export default {
    name: 'NFooter'
  }
</script>

<style lang="scss">
  .footer {
    display: flex;
    justify-content: center;
  }
  .group {
    width: 150px;
  }
  .group-title {
    font-size: 15px;
    font-weight: 500;
    margin-bottom: 15px;
  }
  .group-link {
    a {
      display: block;
      margin-bottom: 10px;
      font-size: 13px;
      text-decoration: none;
      color: rgba(0,0,0,0.44);
      &:hover {
        text-decoration: underline;
        color: #4a4a4a;
      }
    }
  }
</style>

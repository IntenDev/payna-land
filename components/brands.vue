<template>
  <div class="brand">
    <span class="fl-block">
      <p>Trusted by Global Companies</p>
    </span>
    <div class="icon-brend">
      <img src="/img/apple-111.png" alt="Apple">
    </div>
    <div class="icon-brend">
      <img src="/img/Group13.png" alt="Adobe">
    </div>
    <div class="icon-brend">
      <img src="/img/slack-2.png" alt="Slack">
    </div>
    <div class="icon-brend">
      <img src="/img/spotify-11.png" alt="Spotify">
    </div>
    <div class="icon-brend">
      <img src="/img/google-2015.png" alt="Google">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Brand'
}
</script>

<style scoped>
.brand {
  display: flex;
  flex-wrap: wrap;
  /*align-items: start;*/
  margin-top: 100px;
  width: 1272px;
  margin-left: auto;
  margin-right: auto;
}
.icon-brend {
  padding-left: 50px;
  float: right;
}
img {
  height: 30px;
}
span {
  position: relative;
  width: 151px;
  height: 48px;
  float: left;
  font-family: Poppins;
  font-style: normal;
  font-weight: 600;
  font-size: 16px;
  line-height: 24px;
  color: #070F18;
  padding-right: 245px;
  padding-left: 25px;
}
</style>

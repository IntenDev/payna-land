<template>
  <div class="container">
    <div class="manageText">
      <div class="managePay">
        <h1>Manage Payroll Like an Expert</h1>
      </div>
      <span>
        <p>Payna is helping you to setting up the payroll without required any finance skills or knowledge before</p>
      </span>
      <button class="btn">
        Get Started
      </button>
    </div>
    <div class="manageAnalytics">
      <div class="manageImg" />
      <div class="analytics" />
      <div class="builk" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'ManagePay'
}
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  width: 1272px;
  position: relative;
  margin-left: auto;
  margin-right: auto;

}
.manageText {
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  width: 540px;
  height: 400px;
  margin-left: 20px;
  margin-right: 100px;
}
.manageAnalytics {

}
.manageImg {
  background-image: url('/img/image3.png');
  width: 540px;
  height: 400px;
  border-radius: 50px;
}
.analytics {
  background-image: url('/img/Group7.png');
  position: absolute;
  width: 249px;
  height: 191px;
  left: 521px;
  top: 130px;
  z-index: 10;
}
.builk {
  background-image: url('/img/Group6.png');
  position: absolute;
  width: 249px;
  height: 102px;
  left: 1000px;
  top: 41px;
}
h1 {
  font-family: PoppinsB;
  font-style: normal;
  font-weight: bold;
  font-size: 55px;
  line-height: 82px;
  padding-left: 15px;
  color: #000000;
}
span {
  position: relative;
  float: left;
  padding-left: 15px;
  width: 450px;
}
p {
  font-family: Poppins;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 32px;
  /* or 200% */
  color: #575455;
}
.btn {
  position: relative;
  width: 180px;
  height: 48px;
  left: 15px;
  border-radius: 50px;
  font-family: Poppins;
  font-size: 16px;
  background-color: #1F7CFF;
  color: #ffffff;

}
</style>

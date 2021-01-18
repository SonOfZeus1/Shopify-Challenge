<template>
  <div class="banner-bg">
    <div class="banner-img"></div>
    <h1 class="main-head">The Shoppies</h1>
  </div>
</template>

<style scoped>
.banner-bg {
  height: 60vh;
  width: 100%;
  min-width: 500px;
  background: black;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.main-head {
  color: #98f50c;
  font-size: 30px;
  margin-right: 80%;
  margin-bottom: 25%;

  z-index: 100;
}

.banner-img {
  position: absolute;
  background-image: url("../assets/bat.jpg");

  height: 100%;
  width: 100%;
  background-repeat: no-repeat;
  background-position: center center;
  align-items: center;
  background-size: cover;
  filter: saturate(100%);
}
</style>
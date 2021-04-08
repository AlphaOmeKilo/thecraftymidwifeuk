<template>
  <header class="pt-7">
    <div class="text-center">
      <div class="logo" />
      <h1 class="header-title mb-7">The Crafty Midwife UK</h1>
    </div>
  </header>
</template>

<style scoped>
header {
  width: 100%;
  display: flex;
  justify-content: center;
}

.logo {
  height: 140px;
  width: 140px;
  background-image: url("~assets/images/craftymidwifelogo.jpg");
  background-position: center;
  background-size: contain;
  margin: 0 auto;
}

.header-title {
  font-family: "Boulevard", sans-serif;
  font-size: 3rem;
  font-weight: 300;
}
</style>
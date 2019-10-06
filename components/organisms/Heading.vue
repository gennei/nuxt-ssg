<template>
  <div class="heading">
    <p>gennei</p>
    <p>知的好奇心旺盛エンジニア</p>
  </div>
</template>

<style scoped>
.heading {
  height: 300px;
  width: 100%;
  background: center / cover no-repeat url("~assets/header.jpg");
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  z-index: 1;
}
.heading::before {
  content: " ";
  background-color: rgba(0, 0, 0, 0.5);
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  height: 300px;
}
p {
  color: white;
  font-size: 40px;
  font-weight: bold;
  padding: 10px;
  z-index: 2;
}
</style>
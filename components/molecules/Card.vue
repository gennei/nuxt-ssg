<template>
  <div class="container">
    <div class="head">{{ title }}</div>
    <div class="body">
      <p>{{ content }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "card",
  props: {
    title: String,
    content: String
  }
};
</script>

<style scoped>
.container {
  width: 300px;
  box-sizing: border-box;
  border: 1px solid black;
  border-radius: 30px;
}
.head {
  text-align: center;
  width: 100%;
  height: 40px;
  line-height: 40px;
}
.body {
  text-align: center;
  height: 80px;
  line-height: 80px;
}
</style>
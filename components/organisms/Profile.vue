<template>
  <div id="profile-wrapper">
    <div id="profile">
      <div class="introduction">
        コーヒーとサンフレッチェ広島を愛するエンジニア。
        <br />普段はコーヒーをハンドドリップしたり、PHPを書いている。
      </div>
      <div class="likes">
        <span>好きなもの</span>
        <ul>
          <li>読書</li>
          <li>プログラミング</li>
          <li>サンフレッチェ広島</li>
          <li>コーヒー</li>
          <li>ボードゲーム</li>
          <li>PUBG mobile</li>
          <li>勉強</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style scoped>
#profile-wrapper {
  width: 100%;
  padding: 80px 0;
}

#profile {
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  width: 60%;
}

p {
  margin-top: 16px;
}

.likes {
  margin-top: 30px;
}

ul {
  margin-top: 16px;
}

li {
  margin: 8px;
}
</style>
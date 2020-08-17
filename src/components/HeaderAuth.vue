<template>
  <div class="header flex">
      <div class="center">
        <img class="logo" src="../assets/2288.png" alt />
        <p>佐助日記</p>
        <img class="logo" src="../assets/2288.png" alt= />
      </div>
      <div class="right flex">
        <p @click="$router.push('/signup')">新規登録</p>
        <p>／</p>
        <p @click="$router.push('/')">ログイン</p>
      </div>
    </div>
</template>

<style scoped>
.center {
  display: flex;
  margin-top: 50px;
  margin-left: 60px;
}
.center p {
  font-size: 50px;
  padding: 10px;
}
.right {
  align-items: center;
}
.right p {
  margin-right: 20px;
  cursor: pointer;
}
.header {
  margin: 20px;
}
.logo {
  width: 50px;
  cursor: pointer;

}
.flex {
  display: flex;
  justify-content: space-between;
}
</style>
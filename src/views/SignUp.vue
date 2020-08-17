<template>
  <div>
    <HeaderAuth />
    <div class="card">
      <p>新規登録</p>
      <div class="form">
        <input placeholder="ユーザーネーム" type="text" />
        <input placeholder="プロフィール" type="text" />
        <input placeholder="メールアドレス" type="email" />
        <input placeholder="パスワード" type="password" />
        <button @click="auth">新規登録</button>
      </div>
    </div>
  </div>
</template>

<script>
import HeaderAuth from "../components/HeaderAuth";
export default {
  components: {
    HeaderAuth
  }
};
</script>

<style scoped>
button {
  width: 100px;
  text-align: center;
  padding: 8px 0 10px;
  color: black;
  background-color: #ff69b4;
  border-radius: 15px;
  cursor: pointer;
  margin: 20px 0 0 100px;
}
.card {
  margin: 100px auto;
  width: 350px;
  background: #ff69b4;
  border-radius: 5px;
  padding: 20px;
}
.card p {
  color: #fff;
  text-align: center;
}
input {
  margin-top: 15px;
  width: 90%;
  border-radius: 5px;
  padding: 10px;
  border: 1px solid white;
  color: #fff;
}
.form {
  text-align: center;
}
.form button {
  margin-top: 15px;
}
</style>
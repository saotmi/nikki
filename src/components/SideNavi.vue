<template>
  <div>
    <div class="left padding">
      <img class="logo" src="../assets/icon_030350_256.png" alt= />
      <div class="flex icon-field">
        <img class="icon" src="../assets/icon_020010_256.png" alt= />
        <p>ホーム</p> 
      </div>
      <div class="flex-icon-field">
        <img class="logo" src="../assets/icon_030350_256.png" alt= />
        <p>プロフィール</p>
      </div>
      <div class="flex icon-field">
        <img class="icon" src="../assets/2288.png" alt />
        <p>ログアウト</p>
      </div>
    </div>
    <hr />
    <ShareMessage />
  </div>
</template>

<script>
import ShareMessage from "../components/ShareMessage";
export default {
  components: {
    ShareMessage
  }
};
</script>

<style scoped>
.left-padding {
  margin: 20px;
}
.flex {
  display: flex;
}
.logo {
  width: 100px;
}
.icon-field {
  margin-top: 15px;
  cursor: pointer;
}
.icon {
  width: 25px;
}
.icon-field p {
  font-size: 16px;
  padding-left: 15px;
}
</style>
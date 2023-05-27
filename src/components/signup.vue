<template>
  <div class="footer">
    <hr id="footer-hr">
    <span id="account">未註冊帳戶?</span>
    <button id="sign-up" onclick="sign_up()">註冊</button>
  </div>
</template>

<script>
export default {
  name: "signup"
}
</script>

<style scoped>
.footer {
  display: flex;
  flex-flow: column;
  align-items: center;
}

#footer-hr {
  width: 450px;
  margin: 20px auto;
}
#account {
//background-color: pink;
  text-align: center;
  font-weight: 600;
  padding: 16px;
  font-size: 20px;
}
#sign-up {
  background-color: white;
  width: 450px;
  color: #6a6a6a;
  font-weight: bold;
  font-size: 15px;
  height: 45px;
  border: 1px solid gray;
  border-radius: 500px;
  letter-spacing: 0.1rem;
}
</style>
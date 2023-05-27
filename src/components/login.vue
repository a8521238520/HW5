<template>
  <div class="credentials">
    <span id="email-label">電郵地址或用戶名稱</span>
    <label for="email">
      <input type="text" id="email" placeholder="電郵地址或用戶名稱">
    </label>
    <span id="password-label">密碼</span>
    <label>
      <input type="password" id="password" placeholder="密碼">
    </label>
    <a href="https://accounts.spotify.com/en/password-reset?flow_id=e7a22513-1961-43f7-b049-b507394d9aa5%3A1682456236" id="forgot">忘記密碼?</a>
    <label for="remember-label">
      <input type="checkbox" id="remember-label" checked="checked"><span class="checkmark">記住我</span>
    </label>

    <button id="log-in" class="a">登入</button>
  </div>
</template>

<script>
export default {
  name: "login"
}
</script>

<style scoped>
.credentials {
//background-color: lightpink;
  display: flex;
  flex-wrap: wrap;
  width: 450px;
  margin: auto;
  align-items: center;
}
#email-label {
  width: 100%;
  font-size: 14px;
  padding: 4px 0;
  font-weight: bold;
}
#email {
  width: 435px;
  padding: 12px 8px;
  border: 1px solid gray;
  height: 1.5rem;
  border-radius: 4px;
  margin-bottom: 8px;
  font-size: 16px;
}
#password-label {
  width: 100%;
  font-size: 14px;
  padding: 4px 0;
  font-weight: bold;
}
#password {
  width: 435px;
  padding: 12px 8px;
  border: 1px solid gray;
  border-radius: 4px;
  margin-bottom: 8px;
  font-size: 16px;
}
label {
  cursor: default;
}
#log-in {
  background-color: #1ed760;
  color: #6a6a6a;

  border: 1px solid gray;
  border-radius: 500px;

}
.a {
  margin: 10px auto;
  text-align: center;
  justify-content: center;
  align-items: center;
  width: 450px;
  height: 50px;
  display: flex;
  font-weight: 600;
  letter-spacing: 0.1rem;
}

</style>
<template>
  <button id="google" class="app-buttons" onclick="clickGoogle()">

    <img src="google.png" alt="google-icon" class="icons">
    <span> 以 GOOGLE 帳戶繼續</span>
  </button>
</template>

<script>

</script>

<style scoped>
.app-buttons {
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
.icons {
  width: 16px;
}
#google {
  background-color: white;
  color: #6a6a6a;

  border: 1px solid gray;
  border-radius: 500px;

}
</style>
<script>
export default {
  data() {
    return {};
  },
};
</script>

<template>
  <!-- links list -->
  <div class="footer-list">
    <img src="../assets/img/dc-logo-bg.png" alt="" />
  </div>
  <!-- sign up -->
  <div class="sign-in d-flex justify-content-around align-items-center">
    <div class="sign-up-button"><h2>sign up now!</h2></div>
    <div class="follow d-flex gx-3">
      <h3>Follow Us</h3>

      <img src="../assets/img/footer-facebook.png" alt="" class="mx-3 logo" />
      <img src="../assets/img/footer-periscope.png" alt="" class="mx-3 logo" />
      <img src="../assets/img/footer-pinterest.png" alt="" class="mx-3 logo" />
      <img src="../assets/img/footer-twitter.png" alt="" class="mx-3 logo" />
      <img src="../assets/img/footer-youtube.png" alt="" class="mx-3 logo" />
    </div>
  </div>
</template>

<style lang="scss" scoped>
// links - list
.footer-list {
  background-image: url("../assets/img/footer-bg.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  position: absolute;
  width: 100%;
  height: 370px;
  img {
    position: relative;
    left: 55%;
    bottom: 0;
    width: 570px;
    height: 370px;
    object-fit: none;
  }
}
// sign in
.sign-in {
  margin-top: 370px;
  background-color: rgb(43, 42, 42);
  height: 100px;
  color: white;
  .sign-up-button {
    padding: 10px;
    border: 2px solid #0c7cec;
  }
  .follow {
    color: #0c7cec;
  }
  .logo {
    width: 35px;
    height: 35px;
  }
}
</style>

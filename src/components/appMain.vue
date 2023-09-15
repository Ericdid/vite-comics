<script>
export default {
  data() {
    return {
      title: "Hello world",
    };
  },
};
</script>

<template>
  <!-- jumbo -->
  <img src="../assets/img/jumbotron.jpg" alt="" class="w-100 jumbo" />
  <!-- container card -->
  <div class="card-container">
    <div class="row"></div>
  </div>
  <!-- shop -->
  <div class="shop d-flex justify-content-around align-items-center">
    <div>
      <img src="../assets/img/buy-comics-digital-comics.png" class="mx-4" />
      <strong>Digital Comics</strong>
    </div>
    <div>
      <img src="../assets/img/buy-comics-merchandise.png" class="mx-4" />
      <strong>DC Merchandise</strong>
    </div>
    <div>
      <img src="../assets/img/buy-comics-subscriptions.png" class="mx-4" />
      <strong>Subscriptions</strong>
    </div>
    <div>
      <img src="../assets/img/buy-comics-shop-locator.png" class="mx-4" />
      <strong>Comic Shop Locator</strong>
    </div>
    <div>
      <img src="../assets/img/buy-dc-power-visa.svg" class="mx-4" />
      <strong>DC Power Visa</strong>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.jumbo {
  height: 400px;
  object-fit: none;
  object-position: 0 0;
}
.card-container {
  height: 300px;
  background-color: rgb(43, 42, 42);
  color: white;
}
.shop {
  height: 150px;
  background-color: #0c7cec;
  color: white;
  img {
    width: 50px;
    height: 60px;
  }
}
</style>

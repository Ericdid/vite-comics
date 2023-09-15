<script>
export default {
  data() {
    return {
      title: "",
    };
  },
};
</script>

<template>
  <div class="d-flex align-items-center justify-content-around">
    <img src="../assets/img/dc-logo.png" alt="" />
    <ul class="d-flex">
      <li>characters</li>
      <li>comics</li>
      <li>movies</li>
      <li>tv</li>
      <li>games</li>
      <li>collectibles</li>
      <li>videos</li>
      <li>fans</li>
      <li>news</li>
      <li>shop</li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
img {
  display: inline-block;
}
ul {
  list-style-type: none;
  margin: 0;

  li {
    margin-left: 40px;
    margin-top: 2px;
    padding: 40px 5px;
    font-weight: 600;
    border-bottom: 2px solid transparent;
  }
  :hover {
    color: rgb(75, 75, 255);
    border-bottom: 2px solid rgb(75, 75, 255);
  }
}
</style>

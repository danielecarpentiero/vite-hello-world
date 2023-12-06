<template>
  <div class="jumbotron">
    <h1>Benvenuto!</h1>
    <p>Esplora le nostre offerte speciali.</p>
    <a class="btn" href="#">Scopri di più</a>
  </div>
</template>
<script>
export default {
  name: "AppHero",
  data() {
    return {};
  },
};
</script>

<style scoped>
.jumbotron {
  color: #ffffff;
  padding: 50px;
  text-align: center;
  line-height: 50px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  width: 75%;
  margin: 0 auto;
  background-image: url(https://i.redd.it/qchwbp4mgapz.png);
  background-size: cover;
  border-radius: 10px;
}
.btn {
  display: inline-block;
  padding: 10px 20px;
  margin-top: 20px;
  background-color: #ffa500;
  color: #ffffff;
  text-decoration: none;
}
</style>

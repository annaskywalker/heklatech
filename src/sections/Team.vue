<template>
  <div id="team">
    <h1>Team</h1>
    <div class="columns">
      <div class="column image">
        <div class="image-wrapper right">
          <img src="../assets/img/gudjon_frontpage1.jpg" />
          <h2>Gudjon I. Gudjonsson</h2>
          <p>Fysiker</p>
        </div>
      </div>
      <div class="column image">
        <div class="image-wrapper left">
          <img src="../assets/img/carl-magnus1.jpg" />
          <h2>Carl-Magnus Kihlman</h2>
          <p>Mekanisk konstruktör</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Team",
};
</script>

<style scoped>
#team {
  width: 75%;
  margin: 0 auto;
  padding: 3em 0;
  text-align: center;
}
h1 {
  font-size: 50px;
  font-weight: 300;
  color: #fff;
  text-align: center;
  margin: 0 0 0.5em 0;
  position: relative;
}
.image-wrapper img {
  padding: 1em;
  border-radius: 20px;
  max-width: 450px;
}
.left {
    float: left;
}
.right {
  float: right;
}
h2 {
  font-size: 28px;
  margin-bottom: 15px;
  position: relative;
  clear: both;
}
</style>

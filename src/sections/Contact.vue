<template>
  <div id="kontakt">
    <div class="wrapper">
      <h1>Kontakt</h1>
      <div class="columns">
        <div class="column image">
          <img src="../assets/img/heklatech_headquarter1.jpg" />
        </div>
        <div class="column text">
          <h2>Leveransadress</h2>
            <ul>
              <li>Amalia Jönssons gata 19</li>
              <li>42131 Göteborg</li>
            </ul>
          <h2>Fakturaadress</h2>
          <ul>
              <li>Kapplandsgatan 132</li>
              <li>41478 Göteborg</li>
            </ul>
            <br />
            <ul>
              <li>Sverige</li>
              <li>+46 768-232590</li>
              <li>gudjon@gudjon.org</li>
            </ul>
            <a href="https://www.eniro.se/heklatech-ab/134368823/firma?query=Heklatech+AB" target="_blank">Hitta hit på gulasidorna</a>
            <p>Godkänd för F-skatt, MOMS SE-559078453301</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact",
};
</script>

<style scoped>
#kontakt {
  background: #ececec;
  color: #333 !important;
  padding: 3em 0;
}
.wrapper {
  width: 75%;
  margin: 0 auto;
  padding: 0 5em;
  text-align: center;
}
h1 {
  font-size: 50px;
  font-weight: 300;
  color: #333;
  text-align: center;
  margin: 0 0 0.5em 0;
  position: relative;
}
.image img {
  padding: 1em;
  border-radius: 20px;
  max-width: 500px;
  float: right;
}
.text {
  text-align: left;
  padding: 1em 3em;
}
h2 {
  font-size: 28px;
  margin-bottom: 15px;
  position: relative;
}
</style>

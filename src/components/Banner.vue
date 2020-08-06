<template>
  <div id="banner-image">
    <div class="banner-text">
      <h1>Heklatech - <br />Ett mångfacetterat konsultbolag.</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam quis metus
        pulvinar, dapibus mauris vel, euismod erat. Curabitur tempus eu velit
        vel maximus. Nam sed pretium magna, eget suscipit turpis.
      </p>
    </div>
    <div class="arrow" v-scroll-to="{ element: team, offset: -40, duration: 1500 }">
      <img src="../assets/icons/angle-double-down-solid.png" />
    </div>
  </div>
</template>

<script>
import Vue from "vue";
import VueScrollTo from "vue-scrollto";

Vue.use(VueScrollTo);

export default {
  name: "Banner",
  data() {
    return {
      team: '#team'
    };
  },
};
</script>

<style scoped>
@keyframes bounce { 
  0% { top: 16px; opacity: 0; }
  100% { top: 0px; opacity: 1; }
}
#banner-image {
  height: 90vh;
  background-image: url("../assets/img/banner-1.jpg");
  background-size: cover;
  background-position: center;
  position: relative;
}
.arrow {
  height: 60px;
  width: 60px;
  border: 3px solid #fff;
  border-radius: 50%;
  position: absolute;
  bottom: 20px;
  left: 50%;
  text-align: center;
  cursor: pointer;
}
.arrow img {
  color: #fff;
  position: absolute;
  width: 18px;
  right: 18px;
  top: 16px;
}
.arrow:hover img {
  animation: bounce 0.8s;
  animation-direction: alternate;
  animation-iteration-count: infinite;
}
.banner-text {
  position: absolute;
  top: 180px;
  left: 15%;
  /* transform: translatex(-105%); */
  max-width: 750px;
  color: white;
}
h1 {
  font-size: 55px;
  font-weight: 600;
  color: #fff;
  margin: 30px 0;
  position: relative;
  line-height: 65px;
}
p {
  color: #fff;
  max-width: 600px;
  text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.69);
}
</style>

<template>
  <div id="app">
    <Navigation />
    <Banner />
    <Team />
    <Work />
    <Competence />
    <Contact />
    <Map />
    <Footer />
  </div>
</template>

<script>
import Navigation from "./components/Navigation.vue";
import Banner from "./components/Banner.vue";
import Team from "./sections/Team.vue";
import Work from "./sections/Work.vue";
import Competence from "./sections/Competence.vue";
import Contact from "./sections/Contact.vue";
import Map from "./sections/Map.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Navigation,
    Banner,
    Team,
    Work,
    Competence,
    Contact,
    Map,
    Footer
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Raleway:wght@400;500;600&display=swap');

body {
  background: #333;
  font-family: 'Raleway', sans-serif;
  padding-top: 80px !important;
  color: white !important;
}
</style>

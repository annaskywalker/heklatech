<template>
  <div class="nav-container">
    <nav
      class="navbar is-fixed-top"
      role="navigation"
      aria-label="main navigation"
    >
      <div class="navbar-brand">
        <a class="navbar-item logo">
          <img src="../assets/Hekla.svg" width="180px" height="50px" v-scroll-to="{ el: '#banner-image', offset: -80, duration: 1000 }" />
        </a>
      </div>
      <div class="navbar-menu is-active">
        <a
          class="navbar-item"
          v-for="link in links"
          :key="link.id"
          v-scroll-to="{ el: link.id, offset: -40, duration: 1000 }"
        >
          {{ link.name }}
        </a>
      </div>
    </nav>
  </div>
</template>

<script>
import Vue from "vue";
import VueScrollTo from "vue-scrollto";

Vue.use(VueScrollTo);

export default {
  name: "Navigation",
  data() {
    return {
      links: [
        { name: "Team", id: "#team" },
        { name: "Arbete", id: "#arbete" },
        { name: "Kompetens", id: "#kompetens" },
        { name: "Kontakt", id: "#kontakt" },
      ],
    };
  },
};
</script>

<style scoped>
.nav-container {
  background: #222;
  height: 80px;
  left: 0;
  position: fixed;
  right: 0;
  z-index: 30;
  top: 0;
}
.navbar {
  background: #222;
  text-align: center;
  padding: 0.8em;
  max-width: 75%;
  margin: 0 auto;
}
.navbar-item {
  padding: 0 1.5em;
  color: #dedcdc;
}
.logo {
  padding-right: 4em;
}
a.navbar-item:hover {
  background: transparent;
  color: #fff;
}
</style>

<template>
  <div id="kompetens">
    <h1>Kompetenser</h1>
    <div class="columns">
      <div class="column">
        <h2>Programmering</h2>
        <ul>
          <li>C/C++</li>
          <li>Python</li>
          <li>VHDL</li>
          <li>Mikroprocessorer</li>
          <li>Linux PC/Embedded</li>
        </ul>
      </div>
      <div class="column">
        <h2>Mekanisk design</h2>
        <ul>
          <li>Svarvning</li>
          <li>Fräsning</li>
          <li>CAD ritning</li>
        </ul>
      </div>
      <div class="column">
        <h2>Elektronik</h2>
        <ul>
          <li>Analog design</li>
          <li>Digital design</li>
          <li>Prototyper</li>
          <li>Felsökning</li>
          <li>EMC precompliance</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Competence",
};
</script>

<style scoped>
#kompetens {
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
h2 {
  font-size: 28px;
  margin-bottom: 15px;
  position: relative;
}
</style>

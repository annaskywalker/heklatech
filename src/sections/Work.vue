<template>
  <div id="arbete">
    <div class="wrapper">
      <div class="introtext">
        <h1>Vårt arbete</h1>
        <p>
          Heklatech är ett mångfacetterat konsultbolag som specialicerar sig på
          mekanik, elektronik och programmering. Företaget fokuserar på
          helhetslösningar och har kompentens att ta fram prototyper. Det korta
          avståndet mellan fräsen och lödkolven gör det lätt att iterera design
          processen och rätta till eventuella problem.
        </p>
      </div>
      <div class="columns">
        <div class="column image">
          <img src="../assets/img/distance_meter.jpg" />
          <h2>
            Längdmätningar <br />- 3x Enkodrar för kompakta längdmätningar.
          </h2>
          <p>
            Specialbyggd kompakt längdmätnings instrument. Uppgiftern var att
            mäta tre långa rörelser på en liten yta. Detta är löst med små
            rotationsenkodrar. All mekanik och elektronik är byggd på Heklatech.
          </p>
        </div>
        <div class="column image">
          <img src="../assets/img/emc_laboratorium.jpg" />
          <h2>EMC precompliance</h2>
          <p>
            Att hålla koll på utstrålning under design stadiet kan undvika
            problem senare. Vi har utrustning för att mäta utstrålning, både med
            en känslig bredbandsantenn samt närfältsprober, samtidigt.
            Kvalificerade mätningar gör vi hos en partner i ett godkänd
            laboratorium.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Work",
};
</script>

<style scoped>
#arbete {
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
.introtext {
  padding-bottom: 3em;
}
h1 {
  font-size: 50px;
  font-weight: 300;
  color: #333;
  text-align: center;
  margin: 0 0 .5em 0;
  position: relative;
}
p {
  margin: 0 auto;
  width: 80%;
}
h2 {
  font-size: 28px;
  margin-bottom: 15px;
  position: relative;
}
.image img {
  padding: 1em;
  border-radius: 20px;
  max-width: 600px;
  margin: 0 auto;
}
</style>

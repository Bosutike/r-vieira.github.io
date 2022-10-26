<template>
  <div class="flex justify-center pb-20">
    <div class="education">
      <h2>Education</h2>
      <div class="mt-10 md:mr-40 lg:mr-60 xl:mr-80">
        <div class="timeline">
          <div class="timeline-arrow-up"></div>
        </div>
        <div class="timeline-info">
          <div class="master">
            <div class="arrow-left"></div>
            <h4>2020 - 2022</h4>
            <h4>Master's in Computer Science</h4>
            <p>
              <i class="fa-solid fa-xl fa-location-dot mr-2"></i>Faculty of
              Sciences of the University of Lisbon, Portugal
            </p>
          </div>
          <div class="holand">
            <div class="arrow-left"></div>
            <h4>sep 2021 - may 2022</h4>
            <h4>Erasmus+ Internship / Developer</h4>
            <p>
              <i class="fa-solid fa-xl fa-location-dot mr-2"></i>Smart VR Lab,
              Utrecht, Netherlands
            </p>
          </div>
          <div class="bachelor">
            <div class="arrow-left"></div>
            <h4>sep 2017 - july 2020</h4>
            <h4>Bachelor's in Computer Science</h4>
            <p>
              <i class="fa-solid fa-xl fa-location-dot mr-2"></i>University of
              Beira Interior, Covilhã, Portugal
            </p>
          </div>
          <div class="krakow">
            <div class="arrow-left"></div>
            <h4>oct 2019 - feb 2020</h4>
            <h4>Erasmus+ Student Exchange</h4>
            <p>
              <i class="fa-solid fa-xl fa-location-dot mr-2"></i>Politechnika
              Krakowska, Kraków, Poland
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "EducationComponent",
};
</script>

<style scoped>
.education {
  height: 1000px;
}
.timeline {
  position: absolute;
  width: 4px;
  height: 870px;
  background-color: #414141;
}

.timeline-info {
  padding-top: 2em;
}

.timeline-arrow-up {
  position: absolute;
  top: -20px;
  width: 0;
  z-index: 1;
  left: -13px;
  border: medium solid #414141;
  border-width: 0 15px 25px 15px;
  border-color: transparent transparent #414141 transparent;
}

.master {
  position: relative;
  padding: 1.5em;
  margin-left: 40px;
  background-color: #bad1c2;
  border-radius: 1.5em;
}

.holand {
  position: relative;
  padding: 1.5em;
  margin-top: 50px;
  margin-left: 40px;
  background-color: #bad1c2;
  border-radius: 1.5em;
}

.bachelor {
  position: relative;
  padding: 1.5em;
  margin-top: 50px;
  margin-left: 40px;
  background-color: #bad1c2;
  border-radius: 1.5em;
}

.krakow {
  position: relative;
  padding: 1.5em;
  margin-top: 50px;
  margin-left: 40px;
  background-color: #bad1c2;
  border-radius: 1.5em;
}

.arrow-left {
  position: absolute;
  top: 25px;
  width: 0;
  z-index: 1;
  left: -20px;
  border: medium solid #bad1c2;
  border-width: 20px 20px 20px 0;
  border-color: transparent #bad1c2 transparent transparent;
}
</style>

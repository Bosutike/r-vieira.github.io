<template>
  <div id="education" class="flex justify-center sm:py-20 bg-grey">
    <div class="education">
      <h2 class="text-center sm:text-left">Education</h2>
      <div class="sm:mt-10 md:mr-40 lg:mr-60 xl:mr-80">
        <div class="timeline hidden sm:block">
          <div class="timeline-arrow-up"></div>
        </div>
        <div class="timeline-info">
          <div class="master sm:mt-4 mx-1 sm:ml-10">
            <div class="arrow-left hidden sm:block"></div>
            <p>sept 2020 - 2022</p>
            <h4>Master's in Computer Science</h4>
            <h5>
              <i class="fa-solid fa-xl fa-location-dot mr-1"></i>
              Faculty of Sciences of the University of Lisbon, Portugal
            </h5>
          </div>
          <div class="krakow mt-4 sm:mt-8 mx-1 sm:ml-10">
            <div class="arrow-left hidden sm:block"></div>
            <p>oct 2019 - feb 2020</p>
            <h4>Erasmus+ Student Exchange</h4>
            <h5>
              <i class="fa-solid fa-xl fa-location-dot mr-1"></i>
              Politechnika Krakowska, Kraków, Poland
            </h5>
          </div>
          <div class="bachelor mt-4 sm:mt-8 mx-1 sm:ml-10">
            <div class="arrow-left hidden sm:block"></div>
            <p>sept 2017 - july 2020</p>
            <h4>Bachelor's in Computer Science</h4>
            <h5>
              <i class="fa-solid fa-xl fa-location-dot mr-1"></i>
              University of Beira Interior, Covilhã, Portugal
            </h5>
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
.timeline {
  position: absolute;
  width: 4px;
  height: 700px;
  background-color: #414141;
}

.timeline-info {
  padding-top: 0.2em;
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
  background-color: #f0f1f0;
  border-radius: 1.5em;
}

.holand {
  position: relative;
  padding: 1.5em;
  background-color: #f0f1f0;
  border-radius: 1.5em;
}

.bachelor {
  position: relative;
  padding: 1.5em;
  background-color: #f0f1f0;
  border-radius: 1.5em;
}

.krakow {
  position: relative;
  padding: 1.5em;
  background-color: #f0f1f0;
  border-radius: 1.5em;
}

.arrow-left {
  position: absolute;
  top: 25px;
  width: 0;
  z-index: 1;
  left: -20px;
  border: medium solid #f0f1f0;
  border-width: 20px 20px 20px 0;
  border-color: transparent #f0f1f0 transparent transparent;
}
</style>

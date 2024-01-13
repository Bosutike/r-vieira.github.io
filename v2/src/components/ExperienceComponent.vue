<template>
  <div id="work-experience" class="flex justify-center pt-20 pb-10 bg-grey">
    <div class="experience">
      <h2 class="text-center sm:text-right">Work Experience</h2>
      <div class="relative sm:mt-10 md:ml-40 lg:ml-60 xl:ml-80">
        <div class="timeline hidden sm:block">
          <div class="timeline-arrow-up"></div>
        </div>
        <div class="timeline-info text-left sm:text-right">
          <div class="epix mt-4 mx-1 sm:mr-10">
            <div class="arrow-right hidden sm:block"></div>
            <p>oct 2023 - current</p>
            <h4>Full Stack Developer</h4>
            <h5>
              <i class="fa-solid fa-xl fa-location-dot mr-1"></i>
              Freelance, Remote
            </h5>
          </div>
        </div>
        <div class="timeline-info text-left sm:text-right">
          <div class="epix mt-4 mx-1 sm:mr-10">
            <div class="arrow-right hidden sm:block"></div>
            <p>nov 2022 - sept 2023</p>
            <h4>Full Stack Developer</h4>
            <h5>
              <i class="fa-solid fa-xl fa-location-dot mr-1"></i>
              Collab, Lisbon
            </h5>
          </div>
        </div>
        <div class="timeline-info text-left sm:text-right">
          <div class="epix mt-4 mx-1 sm:mr-10">
            <div class="arrow-right hidden sm:block"></div>
            <p>sept 2021 – may 2022</p>
            <h4>Full Stack Developer</h4>
            <h5>
              <i class="fa-solid fa-xl fa-location-dot mr-1"></i>
              Smart VR Lab, Remote
            </h5>
          </div>
        </div>
        <div class="timeline-info text-left sm:text-right">
          <div class="epix mt-4 mx-1 sm:mr-10">
            <div class="arrow-right hidden sm:block"></div>
            <p>may 2021 - july 2021</p>
            <h4>Full Stack Developer</h4>
            <h5>
              <i class="fa-solid fa-xl fa-location-dot mr-1"></i>
              Epix Industries, Remote
            </h5>
          </div>
        </div>
        <div class="timeline-info text-left sm:text-right">
          <div class="everis mt-4 sm:mt-8 mx-1 sm:mr-10">
            <div class="arrow-right hidden sm:block"></div>
            <p>july 2020 - sept 2020</p>
            <h4>Summer Internship / Developer</h4>
            <h5>
              <i class="fa-solid fa-xl fa-location-dot mr-1"></i>
              Everis, Remote
            </h5>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ExperienceComponent",
};
</script>

<style scoped>
.timeline {
  position: absolute;
  width: 4px;
  height: 750px;
  right: 0;
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

.epix {
  position: relative;
  padding: 1.5em;
  background-color: #f0f1f0;
  border-radius: 1.5em;
}

.everis {
  position: relative;
  padding: 1.5em;
  background-color: #f0f1f0;
  border-radius: 1.5em;
}

.arrow-right {
  position: absolute;
  top: 25px;
  width: 0;
  z-index: 1;
  right: -20px;
  border: medium solid #f0f1f0;
  border-width: 20px 0 20px 20px;
  border-color: transparent transparent transparent #f0f1f0;
}
</style>

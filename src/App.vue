<template>
  <NavBarComponent />
  <IntroComponent />
  <ExperienceComponent />
  <EducationComponent />
  <SkillsComponent />
</template>

<script>
import IntroComponent from "./components/IntroComponent.vue";
import ExperienceComponent from "./components/ExperienceComponent.vue";
import EducationComponent from "./components/EducationComponent.vue";
import NavBarComponent from "./components/NavBarComponent.vue";
import SkillsComponent from "./components/SkillsComponent.vue";

export default {
  name: "App",
  components: {
    IntroComponent,
    ExperienceComponent,
    EducationComponent,
    NavBarComponent,
    SkillsComponent,
  },
};
</script>

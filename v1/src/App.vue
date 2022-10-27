<template>
  <NavBarComponent />
  <IntroComponent />
  <ExperienceComponent />
  <EducationComponent />
  <SkillsComponent />
  <ProjectsComponent />
</template>

<script>
import IntroComponent from "./components/IntroComponent.vue";
import ExperienceComponent from "./components/ExperienceComponent.vue";
import EducationComponent from "./components/EducationComponent.vue";
import NavBarComponent from "./components/NavBarComponent.vue";
import SkillsComponent from "./components/SkillsComponent.vue";
import ProjectsComponent from "./components/ProjectsComponent.vue";

export default {
  name: "App",
  components: {
    IntroComponent,
    ExperienceComponent,
    EducationComponent,
    NavBarComponent,
    SkillsComponent,
    ProjectsComponent,
  },
};
</script>

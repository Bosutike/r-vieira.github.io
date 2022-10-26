<template>
  <NavBarComponent />
  <IntroComponent />
  <EducationComponent />
</template>

<script>
import IntroComponent from "./components/IntroComponent.vue";
import EducationComponent from "./components/EducationComponent.vue";
import NavBarComponent from "./components/NavBarComponent.vue";

export default {
  name: "App",
  components: {
    IntroComponent,
    EducationComponent,
    NavBarComponent,
  },
};
</script>

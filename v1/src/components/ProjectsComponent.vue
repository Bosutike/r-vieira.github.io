<template>
  <div id="projects" class="flex justify-center w-full pb-20">
    <div class="container">
      <h2 class="text-center pb-4">Projects</h2>
      <div class="flex justify-center flex-wrap">
        <ProjectComponent
          v-for="project in projects"
          :key="project.id"
          :link="project.link"
          :title="project.title"
          :paragraph="project.paragraph"
          :perks="project.perks"
        />
      </div>
    </div>
  </div>
</template>

<script>
import projects from "../data/projects.json";

import ProjectComponent from "./ProjectComponent.vue";

export default {
  name: "ProjectsComponent",
  components: {
    ProjectComponent,
  },
  data() {
    return {
      projects: projects,
    };
  },
};
</script>

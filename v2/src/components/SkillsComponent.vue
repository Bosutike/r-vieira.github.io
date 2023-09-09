<template>
  <div id="skills" class="flex justify-center w-full pb-20 pt-10 bg-grey">
    <div class="container">
      <h2 class="text-center sm:pb-4">Skills</h2>
      <div class="flex justify-center flex-wrap">
        <div class="container max-w-lg px-4 py-4 border-r-2">
          <h3 class="text-right pb-2 sm:pb-4">Languages</h3>
          <div class="h-2/3 flex justify-between">
            <div class="flex flex-col justify-center space-y-4">
              <span><i class="fa-solid fa-earth-europe mr-2"></i>Portuguese</span>
              <span><i class="fa-solid fa-earth-europe mr-2"></i>English</span>
            </div>
            <div class="flex flex-col justify-center space-y-4">
              <span class="perk">Native</span>
              <span class="perk">Fluent</span>
            </div>
          </div>
        </div>
        <div class="container max-w-lg px-4 py-4 border-l-2">
          <h3 class="pb-2 sm:pb-4">Technologies</h3>
          <div class="flex justify-between">
            <div class="flex flex-col space-y-4">
              <div class="container flex justify-between">
                <span><i class="fa-solid fa-terminal mr-2"></i></span>
                <span class="inline-block align-middle">Programming </span>

                <div class="flex flex-wrap justify-end space-x-2 space-y-2 -mt-2">
                  <span class="perk mt-2 ml-2">.NET</span>
                  <span class="perk">Android</span>
                  <span class="perk">Elixir</span>
                  <span class="perk">Java</span>
                  <span class="perk">JavaScript</span>
                  <span class="perk">Python</span>
                  <span class="perk">TypeScript</span>
                </div>
              </div>
              <div class="container flex justify-between">
                <span><i class="fa-solid fa-window-maximize mr-2"></i>Web</span>
                <div class="flex flex-wrap justify-end space-x-2 space-y-2 -mt-2">
                  <span class="perk mt-2">CSS</span>
                  <span class="perk">HTML</span>
                  <span class="perk">React</span>
                  <span class="perk">Vue.js</span>
                  <span class="perk">Tailwind CSS</span>
                </div>
              </div>
              <div class="container flex justify-between">
                <span><i class="fa-solid fa-database mr-2"></i>DB</span>
                <div class="flex flex-wrap justify-end space-x-2 space-y-2 -mt-2">
                  <span class="perk mt-2">SQL</span>
                  <span class="perk mt-2">PostgreSQL</span>
                  <span class="perk">SQLite</span>
                </div>
              </div>
              <div class="container flex justify-between">
                <span><i class="fa-solid fa-screwdriver-wrench mr-2"></i>Other</span>
                <div class="flex flex-wrap justify-end space-x-2 space-y-2 -mt-2">
                  <span class="perk mt-2">Azure Functions</span>
                  <span class="perk">Docker</span>
                  <span class="perk">GCP</span>
                  <span class="perk">Nginx</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SkillsComponent",
};
</script>

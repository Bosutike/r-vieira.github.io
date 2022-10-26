<template>
  <div class="flex justify-center w-full pb-20">
    <div class="container">
      <h2 class="text-center pb-4">Skills</h2>
      <div class="flex justify-center flex-wrap">
        <div class="container max-w-lg px-4 py-4 border-r-2">
          <h3 class="text-right pb-4">languages</h3>
          <div class="flex justify-between">
            <div class="flex flex-col space-y-4">
              <span
                ><i class="fa-solid fa-earth-europe mr-2"></i>Portuguese</span
              >
              <span><i class="fa-solid fa-earth-europe mr-2"></i>English</span>
            </div>
            <div class="flex flex-col space-y-4">
              <span class="perk">Native</span>
              <span class="perk">Fluent</span>
            </div>
          </div>
        </div>
        <div class="container max-w-lg px-4 py-4 border-l-2">
          <h3 class="pb-4">tecnologies</h3>
          <div class="flex justify-between">
            <div class="flex flex-col space-y-4">
              <div class="container flex justify-between">
                <span><i class="fa-solid fa-computer mr-2"></i></span>
                <span class="inline-block align-middle">Programming </span>

                <div class="flex flex-wrap justify-end space-x-2">
                  <span class="perk">Android Studio</span>
                  <span class="perk">Elixir</span>
                  <span class="perk">Java</span>
                  <span class="perk">JavaScript</span>
                  <span class="perk mt-1">Python</span>
                </div>
              </div>
              <div class="container flex justify-between">
                <span><i class="fa-solid fa-window-maximize mr-2"></i>Web</span>
                <div class="flex flex-wrap justify-end space-x-2">
                  <span class="perk">CSS</span>
                  <span class="perk">HTML</span>
                  <span class="perk">VUE</span>
                </div>
              </div>
              <div class="container flex justify-between">
                <span><i class="fa-solid fa-database mr-2"></i>DB</span>
                <div class="flex flex-wrap justify-end space-x-2">
                  <span class="perk">PostgreSQL</span>
                  <span class="perk">MyQSL</span>
                  <span class="perk">SQLite</span>
                </div>
              </div>
              <div class="container flex justify-between">
                <span
                  ><i class="fa-solid fa-screwdriver-wrench mr-2"></i
                  >Other</span
                >
                <div class="flex flex-wrap justify-end space-x-2">
                  <span class="perk">Docker</span>
                  <span class="perk">Figma</span>
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

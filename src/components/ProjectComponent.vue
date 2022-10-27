<template>
  <div class="drop-shadow-xl p-5 bg-white rounded-md m-1 w-90">
    <div class="flex justify-between px-1">
      <h4 class="mb-4">{{ title }}</h4>
      <span>
        <a :href="link" target="_blank">
          <i class="fa-brands fa-2x fa-github"></i>
        </a>
      </span>
    </div>
    <p class="mb-2">{{ paragraph }}</p>
    <div class="flex justify-end flex-wrap space-x-2 space-y-2 -mt-2">
      <span
        :class="{ 'mt-2': key === 0 }"
        class="perk"
        v-for="(perk, key) in perks"
        :key="key"
        >{{ perk }}</span
      >
    </div>
  </div>
</template>

<script>
export default {
  name: "ProjectComponent",
  props: ["title", "link", "paragraph", "perks"],
};
</script>

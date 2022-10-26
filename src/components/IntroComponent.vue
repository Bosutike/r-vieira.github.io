<template>
  <div id="intro" class="h-screen flex justify-center flex-col text-center">
    <div class="flex justify-center">
      <img
        class="w-52 rounded-full shadow-2xl drop-shadow-2xl"
        v-bind:src="require('../assets/profile.jpg')"
      />
    </div>
    <h1 class="title text-center">Renato Vieira</h1>

    <div class="flex justify-center">
      <div class="flex justify-between w-40">
        <span>
          <a href="mailto:renato.vieira.work@gmail.com" target="_blank">
            <i class="fa-solid fa-2x fa-envelope"></i>
          </a>
        </span>
        <span>
          <a href="https://github.com/Bosutike" target="_blank">
            <i class="fa-brands fa-2x fa-github"></i>
          </a> </span
        ><span>
          <a
            href="https://www.linkedin.com/in/renato-vieira-b41118160/"
            target="_blank"
          >
            <i class="fa-brands fa-2x fa-linkedin"></i>
          </a> </span
        ><span>
          <a href="" target="_blank">
            <i class="fa-solid fa-2x fa-file"></i>
          </a>
        </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "IntroComponent",
};
</script>

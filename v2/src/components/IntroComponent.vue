<template>
  <div id="intro" class="relative h-screen">
    <div class="absolute bg-grey top-[40%] w-full h-[60%]"></div>

    <div class="absolute top-[40%] left-1/2 -translate-x-1/2 -translate-y-1/2">
      <img
        class="w-[275px] min-w-[150px] rounded-full"
        v-bind:src="require('../assets/profile.jpg')"
      />
      <div class="relative">
        <div class="absolute top-2 left-1/2 -translate-x-1/2 whitespace-nowrap">
          <h1 class="title text-center leading-none pb-5">Renato Vieira</h1>

          <div class="flex justify-center">
            <div class="flex justify-between w-40">
              <span>
                <a href="mailto:renato.vieira.work@gmail.com" target="_blank">
                  <i class="fa-solid fa-2x fa-envelope hover:scale-125"></i>
                </a>
              </span>
              <span>
                <a href="https://github.com/Bosutike" target="_blank">
                  <i class="fa-brands fa-2x fa-github hover:scale-125"></i>
                </a> </span
              ><span>
                <a
                  href="https://www.linkedin.com/in/renato-vieira-b41118160/"
                  target="_blank"
                >
                  <i class="fa-brands fa-2x fa-linkedin hover:scale-125"></i>
                </a>
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "IntroComponent",
};
</script>

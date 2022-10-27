<template>
  <nav
    :class="{ 'shadow-md': !atTopOfPage }"
    class="fixed w-full flex flex-wrap items-center justify-between px-2 py-3 top-0"
  >
    <div
      class="container px-4 mx-auto flex flex-wrap items-center justify-between"
    >
      <div
        class="w-full relative flex justify-between lg:w-auto px-4 lg:static lg:block lg:justify-start"
      >
        <a
          class="font-bold leading-relaxed inline-block mr-4 py-2 whitespace-nowrap uppercase"
          href="#pablo"
        >
          r_vieira
        </a>
        <button
          class="cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none"
          type="button"
          v-on:click="toggleNavbar()"
        >
          <i class="fas fa-bars"></i>
        </button>
      </div>
      <div
        v-bind:class="{ hidden: !showMenu, flex: showMenu }"
        class="lg:flex lg:flex-grow items-center"
      >
        <ul class="flex flex-col lg:flex-row list-none ml-auto">
          <li class="nav-item">
            <a
              class="px-3 py-2 flex items-center uppercase font-bold leading-snug hover:opacity-75"
              href="#work-experience"
            >
              <span class="ml-2">Work Experience</span>
            </a>
          </li>
          <li class="nav-item">
            <a
              class="px-3 py-2 flex items-center uppercase font-bold leading-snug hover:opacity-75"
              href="#education"
            >
              <span class="ml-2">Education</span>
            </a>
          </li>
          <li class="nav-item">
            <a
              class="px-3 py-2 flex items-center uppercase font-bold leading-snug hover:opacity-75"
              href="#skills"
              ><span class="ml-2">Skills</span>
            </a>
          </li>
          <li class="nav-item">
            <a
              class="px-3 py-2 flex items-center uppercase font-bold leading-snug hover:opacity-75"
              href="#projects"
            >
              <span class="ml-2">Projects</span>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "EducationComponent",
  data() {
    return {
      atTopOfPage: true,
      showMenu: false,
    };
  },

  mounted() {
    window.addEventListener("scroll", this.handleScroll);
  },
  beforeUnmount() {
    window.removeEventListener("scroll", this.handleScroll);
  },

  methods: {
    toggleNavbar: function () {
      this.showMenu = !this.showMenu;
    },

    handleScroll() {
      if (window.pageYOffset > 0) {
        if (this.atTopOfPage) this.atTopOfPage = false;
      } else {
        if (!this.atTopOfPage) this.atTopOfPage = true;
      }
    },
  },
};
</script>

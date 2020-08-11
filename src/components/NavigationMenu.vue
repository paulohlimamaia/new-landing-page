<template>
<nav class="p-10">
    <div>
      <button @click="toggleMenu" class="flex items-center text-black focus:outline-none">
        <svg class="fill-current h-5 w-5" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
          <title>Menu</title>
          <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/>
        </svg>
      </button>
    </div>
</nav>
</template>

<script>
import AppLogo from "./AppLogo.vue";

export default {
  components: {
    AppLogo
  },
  data() {
    return {
      menu: true
    };
  },
  methods: {
    toggleMenu() {
      this.menu = !this.menu
    }
  },
};
</script>

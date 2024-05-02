<script>
import AppBanner from "./components/AppBanner.vue";

export default {
  components: {
    AppBanner,
  },
  data() {
    return {
      title: "La mia prima app con VITE!",
    };
  },
};
</script>

<template>
  <h1>{{ title }}</h1>

  <section>
    <AppBanner />
  </section>
</template>

<style></style>

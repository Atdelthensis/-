<template>
  <component :is="layout">
    <RouterView />
  </component>
</template>

<script>
import Main from "@/layout/main.vue"

export default {
  components : {
    Main,  },
  computed: {
    layout() {
      console.log(this.$route.meta);
      return this.$route.meta.layout || Main;
    },
  },
};
</script>
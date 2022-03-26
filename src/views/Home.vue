<template>
  <div class="home">
    <Frontpage msg="Creating an app in Vue.js (Vue 3)" />
  </div>
</template>

<script>
import Frontpage from "@/components/Frontpage.vue";

export default {
  name: "Home",
  components: {
    Frontpage
  }
};
</script>

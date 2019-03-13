<template>
  <div id="app">
    <navbar />
    <div class="container">
      <router-view />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import navbar from "@/components/Navbar.vue";

export default {
  name: "home",
  components: {
    navbar
  }
};
</script>

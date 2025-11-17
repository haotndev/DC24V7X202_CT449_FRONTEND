<script>
import AppHeader from "@/components/AppHeader.vue";
export default {
  components: {
    AppHeader,
  },
};
</script>

<template>
  <div id="app" style="width: 100vw; height: 100vh" class="d-flex flex-column">
    <AppHeader />
    <div class="container mt-3 d-fex justify-content-center">
      <router-view />
    </div>
  </div>
</template>

<style>
.page {
  max-width: 400px;
  margin: auto;
}
</style>

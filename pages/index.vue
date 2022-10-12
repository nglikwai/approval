<template>
  <div class="container">
    <SideBar />
  </div>
</template>

<script>
import SideBar from "../components/SideBar.vue";
export default {
  name: "IndexPage",
  components: { SideBar },
};
</script>

<style scoped>
.container {
  display: flex;
}
</style>

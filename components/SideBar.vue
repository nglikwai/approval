<template>
  <div class="menu">
    <div class="menu-item">HOME</div>
    <div class="menu-item">APPLICATION</div>
    <div class="menu-item">IN PROGRESS</div>
    <div class="menu-item">HISTORY</div>
  </div>
</template>

<script>
export default {
  name: "sidebar",
};
</script>

<style lang="scss" scoped>
.menu {
  background-color: #fcfcfc;
  box-shadow: 0 0 8px #ccc;
  height: 100vh;
  padding: 30px;
}

.menu-item {
  padding: 20px;
}
</style>

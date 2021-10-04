<template>
  <header>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style lang="scss" scoped>
header {
  position: fixed;
}
</style>

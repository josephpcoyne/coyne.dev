<template>
  <div id="app">
    <NavBar class="inset-x-0 top-0 fixed" />

    <router-view />
  </div>
</template>
<script>
import NavBar from "@/components/NavBar.vue";

export default {
  components: {
    NavBar
  }
};
</script>
<style>
#app {
  font-family: 'Roboto', sans-serif;
  /* font-family: -apple-system, BlinkMacSystemFont, Helvetica Neue, Roboto, Arial,
    Noto Sans, sans-serif, Apple Color Emoji, Segoe UI, Segoe UI Emoji,
    Segoe UI Symbol, Noto Color Emoji;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; */
  /* text-align: center; */
  color: #2c3e50;
  /* padding: 3rem 10rem; */
}
/* .font {
  font-family: Gilroy-ExtraBold;
}
.font-medium {
  font-family: Gilroy-Medium;
} */
</style>

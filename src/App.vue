<template>
  <Nav></Nav>
  <div class="container mt-4">
    <router-view />
  </div>
</template>
<script>
import Nav from "./views/Nav.vue";
export default {
  components: {
    Nav,
  },
};
</script>
<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap");

#app {
  font-family: "Roboto", sans-serif;
}

a {
  color: inherit !important;
}
</style>

<template>
  <main id="app">
    <menu-mobile />
  </main>
</template>

<script>
import MenuMobile from "./components/MenuMobile.vue";

export default {
  name: "App",
  components: {
    MenuMobile,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto+Flex:opsz,wght@8..144,100;8..144,200;8..144,300;8..144,400;8..144,500;8..144,600;8..144,700;8..144,800;8..144,900;8..144,1000&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Roboto Flex", sans-serif;
}

body {
  display: flex;
  flex-direction: column;
}

a {
  text-decoration: none;
}

#app {
  width: 375px;
  margin: auto;
  margin-top: 12px;
  border: 1px solid #ccc;
  border-radius: 24px;
}
</style>

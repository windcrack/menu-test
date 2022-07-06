<template>
  <div>
    <section class="container">
      <Header />
      <GeniusCard />
      <MenuItems />
    </section>
    <Footer />
  </div>
</template>

<script>
import Header from "./Header.vue";
import GeniusCard from "./GeniusCard.vue";
import MenuItems from "./MenuItems.vue";
import Footer from "./Footer.vue";

export default {
  name: "Menu Mobile Body",
  components: {
    Header,
    GeniusCard,
    MenuItems,
    Footer,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass">
.container
	display: flex
	flex-direction: column
	width: 100%
	padding: 0 20px
</style>

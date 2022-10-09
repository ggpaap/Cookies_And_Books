<script>
import HeaderComp from "@/components/template/HeaderComp.vue";
import FooterComp from "@/components/template/FooterComp.vue";

export default {
  components: { HeaderComp, FooterComp },
};
</script>

<template>
  <HeaderComp />
  <main><RouterView /></main>
  <FooterComp />
</template>
<style>
#app {
  max-height: 1200px;
  margin: 0 auto;
  height: 100vh;
  font-weight: normal;
}

main {
  height: 80%;
}
a {
  color: inherit;
  text-decoration: none;
}

</style>

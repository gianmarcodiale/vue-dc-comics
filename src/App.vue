<template>
  <div id="app">
    <SiteHeader/>
    <main>
      <h1>-> Content goes here</h1>
    </main>
    <SiteShopSection/>
    <SiteFooter/>
  </div>
</template>

<script>
import SiteHeader from "@/components/HeaderComponent.vue";
import SiteShopSection from "@/components/ShopSectionComponent.vue"
import SiteFooter from "@/components/FooterComponent.vue"

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteShopSection,
    SiteFooter
  }
}
</script>

<style lang="scss">
main {
  background-color: black;
  min-height: 150px;
  h1 {
    color: white;
  }
}
</style>

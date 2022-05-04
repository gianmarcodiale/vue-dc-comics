<template>
  <div id="app">
    <SiteHeader/>
    <main>
      <h1>-> Content goes here</h1>
    </main>
    <SiteShopSection/>
    <SiteFooter/>
    <SiteSocials/>
  </div>
</template>

<script>
import SiteHeader from "@/components/HeaderComponent.vue";
import SiteShopSection from "@/components/ShopSectionComponent.vue";
import SiteFooter from "@/components/FooterComponent.vue";
import SiteSocials from "@/components/SocialsComponent.vue"

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteShopSection,
    SiteFooter,
    SiteSocials
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

<template>
  <div id="app">
    <SiteHeader/>
    <main>
      <h1>-> Content goes here</h1>
    </main>
    <SiteShopSection/>
  </div>
</template>

<script>
import SiteHeader from "@/components/HeaderComponent.vue";
import SiteShopSection from "@/components/SiteShopSectionComponent.vue"

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteShopSection
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

<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <HeaderShayna />
    <HeroShayna />
    <WomanShayna />
    <InstaShayna />
    <PatnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from "@/components/HeaderShayna.vue"
import HeroShayna from "@/components/HeroShayna.vue"
import WomanShayna from "@/components/WomanShayna.vue"
import InstaShayna from "@/components/InstaShayna.vue"
import PatnerShayna from "@/components/PatnerShayna.vue"
import FooterShayna from "@/components/FooterShayna.vue"

export default {
  name: "home",
  components: {
    HeaderShayna,
    HeroShayna,
    WomanShayna,
    InstaShayna,
    PatnerShayna,
    FooterShayna
  }
}
</script>

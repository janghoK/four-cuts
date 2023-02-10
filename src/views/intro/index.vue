<template>
  <HeroSection />
  <ButtonSection />
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HeroSection from "./hero/hero.vue";
import ButtonSection from "./button/button.vue";

@Options({
  components: { HeroSection, ButtonSection },
})
export default class HeroView extends Vue {}
</script>

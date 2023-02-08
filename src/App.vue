<template>
  <router-view />
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  components: {},
})
export default class App extends Vue {}
</script>

<style lang="less">
@import "./views/styles/style.less";
</style>

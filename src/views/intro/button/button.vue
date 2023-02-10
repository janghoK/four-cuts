<template>
  <div class="container">
    <div class="button-group">
      <button class="mint-color">4컷 사진 찍기</button>
      <button class="pink-color">4컷 사진 만들기</button>
      <button class="kakao-color">친구들에게 공유하기</button>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
@Options({
  components: {},
})
export default class ButtonSection extends Vue {}
</script>

<style lang="less">
@import "./button.less";
</style>

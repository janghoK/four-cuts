<template>
  <div class="container">
    <div class="hero">
      <div class="hero-title">
        <div class="title">W e b 4 컷</div>
      </div>

      <div class="hero-image">
        <div class="image-wrapper">
          <div class="four-cut-image" style="transform: rotate(-5deg)">
            <img
              class="image-section"
              src="../../../assets/images/sample1.jpeg"
            />
            <img
              class="image-section"
              src="../../../assets/images/sample2.jpeg"
            />
            <img
              class="image-section"
              src="../../../assets/images/sample3.jpeg"
            />
            <img
              class="image-section"
              src="../../../assets/images/sample4.jpeg"
            />
          </div>
        </div>
        <div>
          <div class="description right">
            웹에서 4컷 사진을 찍어보세요.<br />
            생각보다 재미있습니다.<br /><br />
            사진, 동영상은 서버에 저장되지 않습니다.<br /><br />
            접속한 단말기에서 카메라가 인식되는 경우만 촬영이 가능합니다.
          </div>
        </div>
      </div>

      <div class="hero-image">
        <div>
          <div class="description">
            카메라가 없어도 걱정하지 마세요.<br /><br />
            업로드 기능으로<br />
            4컷 사진을 만들 수 있습니다. (포토샵 하고 올려도 됨)<br /><br />
            당연히 서버에 저장되지는 않습니다.
          </div>
        </div>

        <div class="image-wrapper">
          <div class="four-cut-image" style="transform: rotate(5deg)">
            <img
              class="image-section"
              src="../../../assets/images/sample5.jpg"
            />
            <img
              class="image-section"
              src="../../../assets/images/sample6.jpeg"
            />
            <img
              class="image-section"
              src="../../../assets/images/sample7.png"
            />
            <img
              class="image-section"
              src="../../../assets/images/sample8.jpeg"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  components: {},
})
export default class HeroSection extends Vue {}
</script>

<style lang="less">
@import "./hero.less";
</style>

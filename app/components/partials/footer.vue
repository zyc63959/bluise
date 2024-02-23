<template>
  <footer class="footer -mx-4 md:mx-0">
    <div class="container mx-auto pb-6 flex justify-center">
      <a style="color:#666" target="_blank" rel="noopener external nofollow noreferrer" href="http://beian.miit.gov.cn/">豫ICP备19040382号</a>
    </div>
  </footer>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator';

@Component
export default class Footer extends Vue {}
</script>

<style lang="scss">
.footer {
  background-color: $bluise;
}
</style>

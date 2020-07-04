<template>
  <footer class="footer -mx-4 md:mx-0">
    <div class="container mx-auto pb-6 flex justify-center">
      <a href="https://merake.net">
        <img src="https://merake.net/wp-content/uploads/2020/04/cropped-merake%CC%80-logo-300x61.png" width="150px" height="auto" alt="meraké lab">
      </a>
    </div>
  </footer>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Footer extends Vue {}
</script>

<style lang="scss">
.footer {
  background-color: $bluise;
}
</style>

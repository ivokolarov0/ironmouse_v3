<template>
  <div class="ironmouse">
    <div class="ironmouse__legs">
      <leg />
      <leg :right="true" />
    </div>
    <div class="ironmouse__boots">
      <boot />
      <boot class="reverse" />
    </div>
  </div>
</template>

<script>
import boot from '../boot/boot.vue';
import Leg from '../leg/leg.vue';
export default {
  components: { boot, Leg },
};
</script>

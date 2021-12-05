<template>
  <div class="chest">
    <div class="chest-wrapper">
      <div class="chest__inner">
        <collarbone />
        <div class="chest__holder"></div>
      </div>
    </div>
    <arm-belt class="left" />
    <arm-belt class="right" />
    <arms />
    <sweater />
  </div>
</template>

<script>
import ArmBelt from '../arm-belt/arm-belt.vue';
import arms from '../arms/arms.vue';
import Collarbone from '../collarbone/collarbone.vue';
import Sweater from '../sweater/sweater.vue';

export default {
  components: { arms, ArmBelt, Collarbone, Sweater },
};
</script>

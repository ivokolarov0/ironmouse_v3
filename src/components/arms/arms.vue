<template>
  <div class="arms">
    <arm>
      <hand-pins class="bottom" />
    </arm>
    <arm>
      <hand-pins class="top" />
    </arm>
  </div>
</template>

<script>
import HandPins from '../hand-pins/hand-pins.vue';
import arm from './arm.vue';
export default {
  components: { arm, HandPins },
};
</script>

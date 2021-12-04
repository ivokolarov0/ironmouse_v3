<template>
  <div class="face">
    <div class="face__side">
      <div class="face__left">
        <div class="face__bottom"></div>
      </div>
      <div class="eyebrow">
        <div class="eyebrow__inner"></div>
      </div>
      <div class="mouth"></div>
      <div class="nose"></div>
      <eye />
    </div>
  </div>
</template>

<script>
import Eye from '../eye/eye.vue';

export default {
  components: {
    Eye,
  },
};
</script>

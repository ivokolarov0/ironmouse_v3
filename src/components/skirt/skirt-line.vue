<template>
  <div class="skirt-line">
    <div class="skirt-line-outer">
      <div class="skirt-line__stripe" :class="color"></div>
      <div class="skirt-line__heart">
        <heart class="white" />
        <heart class="white" />
        <heart class="white" />
      </div>
      <!-- /.skirt-line__heart -->
      <div class="skirt-line__holder">
        <slot />
      </div>
    </div>
  </div>
</template>

<script>
import heart from '../heart/heart.vue';

export default {
  props: {
    color: {
      type: String,
      default: 'purple',
    },
  },
  components: { heart },
};
</script>

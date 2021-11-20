<template>
  <div class="sock-pink">
    <div class="sock-pink__top" v-if="type === 'top'">
      <div class="sock-pink__top-border">
        <div class="sock-pink__top-border-holder">
          <div class="sock-pink__top-border-inner"></div>
        </div>
      </div>
      <div class="sock-pink__top-inner"></div>
    </div>
    <div class="sock-pink__bottom" v-if="type === 'bottom'">
      <div class="sock-pink__bottom-inner"></div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    type: {
      type: String,
      default: 'top',
    },
  },
};
</script>

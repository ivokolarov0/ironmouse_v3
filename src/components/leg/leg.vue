<template>
  <div class="leg" :class="{ 'is-right': right }">
    <div class="leg__bottom">
      <div class="leg__inner">
        <div class="leg__side">
          <slot name="bottom" />
        </div>
      </div>
    </div>
    <div class="leg__top">
      <div class="leg__top-inner">
        <slot name="top" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['right'],
};
</script>

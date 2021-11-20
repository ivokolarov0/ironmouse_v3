<template>
  <div class="leg" :class="{ 'is-right': right }">
    <div class="leg-straps" v-if="!right">
      <div class="leg-straps-line leg-straps-line--top"></div>
      <div class="leg-straps-line leg-straps-line--bottom"></div>
      <div class="leg-straps__cirlce">
        <div class="leg-straps__cirlce-inner"></div>
      </div>
      <div class="leg-straps__belt leg-straps__belt--left">
        <div class="leg-straps__belt-inner">
          <div class="legs-straps__belt-item">
            <div class="leg-straps__belt-hole"></div>
          </div>
        </div>
      </div>
      <div class="leg-straps__belt leg-straps__belt--right">
        <div class="leg-straps__belt-inner">
          <div class="legs-straps__belt-item">
            <div class="leg-straps__belt-hole"></div>
          </div>
        </div>
      </div>
      <div class="leg-straps__overlay"></div>
    </div>
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

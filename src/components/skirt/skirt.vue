<template>
  <div class="ironmouse__skirt">
    <div class="skirt-belt-top">
      <heart />
      <div class="skirt-belt-top__inner"></div>
    </div>
    <div class="skirt-belt-bottom">
      <div class="skirt-belt-bottom__inner"></div>
      <div class="skirt-belt-buckle">
        <div class="skirt-belt-buckle__left"></div>
        <div class="skirt-belt-buckle__right"></div>
        <div class="skirt-belt-buckle__pin">
          <span></span>
        </div>
      </div>
    </div>
    <div class="skirt-lines">
      <div class="skirt-line">
        <div class="skirt-line__holder">
          <div class="skirt-line__inner"></div>
        </div>
      </div>
      <div class="skirt-line">
        <div class="skirt-line__holder">
          <div class="skirt-line__inner"></div>
        </div>
      </div>
      <div class="skirt-line">
        <div class="skirt-line__holder">
          <div class="skirt-line__inner"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import heart from '../../assets/scss/components/heart/heart.vue';

export default {
  components: { heart },
};
</script>

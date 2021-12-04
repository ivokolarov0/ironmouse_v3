<template>
  <div class="head">
    <div class="horns">
      <div class="horn-outer">
        <div class="horn">
          <div class="horn__inner"></div>
        </div>
      </div>
      <div class="horn-outer">
        <div class="horn">
          <div class="horn__inner"></div>
        </div>
      </div>
    </div>
    <face class="face--left" />
    <face class="face--right" />
  </div>
</template>

<script>
import face from '../face/face.vue';
export default {
  components: { face },
};
</script>

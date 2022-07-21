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
    <div class="ears">
      <div class="ear">
        <div class="ear__inner"></div>
      </div>
      <div class="ear">
        <div class="ear__inner"></div>
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

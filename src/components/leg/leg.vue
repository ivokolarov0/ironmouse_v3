<template>
  <div class="leg" :class="{ 'is-right': right }">
    <div class="leg__bottom">
      <div class="leg__inner">
        <div class="leg__side">
          <template v-if="!right">
            <div class="sock-purple">
              <div class="sock-purple__inner"></div>
            </div>
            <div class="sock-purple__top">
              <div class="sock-purple__top-inner"></div>
            </div>
            <div class="sock-purple__crosses">
              <div class="sock-purple__cross">
                <span></span>
                <span></span>
              </div>
              <div class="sock-purple__cross">
                <span></span>
                <span></span>
              </div>
              <div class="sock-purple__cross">
                <span></span>
                <span></span>
              </div>
            </div>
          </template>
        </div>
      </div>
    </div>
    <div class="leg__top">
      <div class="leg__top-inner"></div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['right'],
};
</script>

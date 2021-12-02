<template>
  <div class="ironmouse">
    <Head />
    <div class="sleave-top-holder">
      <div class="sleave-top-behind">
        <div class="sleave-top-behind__inner"></div>
      </div>
      <div class="sleave-top-behind sleave-top-behind--right">
        <div class="sleave-top-behind__inner"></div>
      </div>
    </div>
    <chest />
    <tail />
    <skirt />
    <div class="ironmouse__legs">
      <leg>
        <template #bottom>
          <sock-purple />
        </template>
      </leg>
      <leg :right="true">
        <template #top>
          <sock-pink type="top" />
        </template>
        <template #bottom>
          <sock-pink type="bottom" />
        </template>
      </leg>
      <div class="sock-pink__top-patch">
        <div class="sock-pink__top-patch-t">
          <div class="sock-pink__top-patch-l">
            <div class="sock-pink__top-patch-r"></div>
          </div>
        </div>
        <div class="sock-pink__top-lines">
          <div class="sock-pink__top-lines-inner">
            <span></span>
            <span></span>
          </div>
          <div class="sock-pink__top-lines-inner">
            <span></span>
            <span></span>
          </div>
        </div>
      </div>
    </div>
    <div class="ironmouse__boots">
      <boot />
      <boot class="reverse" />
    </div>
  </div>
</template>

<script>
import Chest from '../chest/chest.vue';
import boot from '../boot/boot.vue';
import Leg from '../leg/leg.vue';
import Skirt from '../skirt/skirt.vue';
import SockPink from '../sock-pink/sock-pink.vue';
import SockPurple from '../sock-purple/sock-purple.vue';
import Tail from '../tail/tail.vue';
import Head from '../head/head.vue';

export default {
  components: { boot, Leg, SockPurple, SockPink, Skirt, Chest, Tail, Head },
};
</script>

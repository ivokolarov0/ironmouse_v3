<template>
  <div class="boot">
    <boot-bottom />
    <boot-back />
    <boot-ties />
    <boot-front />
    <boot-top />
    <boot-ribbon />
  </div>
</template>

<script>
import BootBack from './boot-back.vue';
import bootBottom from './boot-bottom.vue';
import BootFront from './boot-front.vue';
import BootRibbon from './boot-ribbon.vue';
import BootTies from './boot-ties.vue';
import BootTop from './boot-top.vue';
export default {
  components: {
    bootBottom,
    BootFront,
    BootBack,
    BootTies,
    BootTop,
    BootRibbon,
  },
};
</script>

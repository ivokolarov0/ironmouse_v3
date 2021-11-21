<template>
  <div class="ironmouse__skirt">
    <skirt-under />
    <skirt-belt-top />
    <skirt-belt-bottom />
    <div class="skirt-crosses skirt-crosses--top">
      <skirt-cross />
      <skirt-cross class="purple" />
    </div>
    <div class="skirt-lines">
      <skirt-line>
        <div class="skirt-line__inner">
          <div class="skirt-line__hole"></div>
        </div>
      </skirt-line>
      <skirt-line color="pink">
        <div class="skirt-line__inner"></div>
      </skirt-line>
      <skirt-line>
        <div class="skirt-line__inner"></div>
      </skirt-line>
      <skirt-line color="pink">
        <div class="skirt-line__inner">
          <div class="skirt-line__hole"></div>
        </div>
      </skirt-line>
      <skirt-line>
        <div class="skirt-line__inner"></div>
      </skirt-line>
      <skirt-line>
        <div class="skirt-line__inner"></div>
      </skirt-line>
      <skirt-line>
        <div class="skirt-crosses">
          <skirt-cross />
          <skirt-cross class="purple" />
        </div>
        <div class="skirt-line__transparent">
          <div class="skirt-line__transparent-left">
            <div class="skirt-line__transparent-right"></div>
          </div>
        </div>
      </skirt-line>
    </div>
  </div>
</template>

<script>
import SkirtBeltBottom from './skirt-belt-bottom.vue';
import SkirtBeltTop from './skirt-belt-top.vue';
import SkirtCross from './skirt-cross.vue';
import SkirtLine from './skirt-line.vue';
import SkirtUnder from './skirt-under.vue';

export default {
  components: {
    SkirtCross,
    SkirtLine,
    SkirtUnder,
    SkirtBeltTop,
    SkirtBeltBottom,
  },
};
</script>

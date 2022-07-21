<template>
  <div class="hair">
    <div class="hair__side">
      <div class="hair-loops">
        <div class="hair-loop">
          <div class="hair-loop__inner">
            <div class="hair-loop__circle1"></div>
            <div class="hair-loop__circle2"></div>
          </div>
        </div>
        <div class="hair-loop">
          <div class="hair-loop__inner">
            <div class="hair-loop__circle1-wrapper">
              <div class="hair-loop__circle1"></div>
            </div>
          </div>
        </div>
      </div>
      <div class="hair-parts1">
        <div class="hair-part" v-for="(item, index) in 29" :key="index">
          <div class="hair-part__inner"></div>
        </div>
      </div>
      <div class="hair-parts2">
        <div class="hair-part" v-for="(item, index) in 29" :key="index">
          <div class="hair-part__inner"></div>
        </div>
      </div>
    </div>
    <div class="hair__side">
      <div class="hair-loops">
        <div class="hair-loop">
          <div class="hair-loop__inner">
            <div class="hair-loop__circle1"></div>
            <div class="hair-loop__circle2"></div>
          </div>
        </div>
        <div class="hair-loop">
          <div class="hair-loop__inner">
            <div class="hair-loop__circle1-wrapper">
              <div class="hair-loop__circle1"></div>
            </div>
          </div>
        </div>
      </div>
      <div class="hair-parts1">
        <div class="hair-part" v-for="(item, index) in 29" :key="index">
          <div class="hair-part__inner"></div>
        </div>
      </div>

      <div class="hair-parts2">
        <div class="hair-part" v-for="(item, index) in 29" :key="index">
          <div class="hair-part__inner"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

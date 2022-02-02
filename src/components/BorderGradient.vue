<template>
  <div class="borderGradient"></div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.borderGradient {
  border: 1px solid map-get($font-color, 'darkGrey');
  width: 95%;
  margin: map-get($font-space, 'spacing');
}
</style>

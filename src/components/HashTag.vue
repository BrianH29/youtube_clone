<template>
  <div class="hashtag">
    <ul>
      <li>#nbafinal</li>
      <li>#highlight</li>
      <li>#warriorsvsrockets</li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.hashtag {
  padding: 12px 12px 0;

  ul {
    display: flex;
    list-style: none;
    color: map-get($font-color, 'hashBlue');
    font-size: map-get($font-size, 'small');

    li {
      margin-right: map-get($font-space, 'spacing');
    }
  }
}
</style>

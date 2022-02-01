<template>
  <section class="hashtag">
    <ul>
      <li>#nbafinal</li>
      <li>#highlight</li>
      <li>#warriorsvsrockets</li>
    </ul>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.hashtag {
  background: map-get($font-color, 'black');
  padding: map-get($font-space, 'spacing');

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

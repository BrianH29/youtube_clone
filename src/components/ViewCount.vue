<template>
  <div class="viewCount">
    <span>조회수</span>
    <span>100,230회</span>
    <span>2022.02.01</span>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.viewCount {
  color: map-get($font-color, 'darkGrey');
  font-size: map-get($font-size, 'small');

  span {
    margin-right: 5px;
  }
}
</style>

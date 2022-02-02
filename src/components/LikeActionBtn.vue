<template>
  <div class="actionBtn">
    <ul class="actionBtn__icon">
      <li>
        <i class="far fa-thumbs-up"></i>
        <span>2.5mil</span>
      </li>
      <li>
        <i class="far fa-thumbs-down"></i>
        <span>싫어요</span>
      </li>
      <li>
        <i class="fas fa-share"></i>
        <span>공유</span>
      </li>
      <li>
        <i class="fas fa-plus"></i>
        <span>저장</span>
      </li>
      <li><i class="fas fa-ellipsis-h"></i></li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.actionBtn {
  #{&}__icon {
    display: flex;
    list-style: none;
    color: map-get($font-color, 'white');

    li {
      margin-right: map-get($font-space, 'spacing');

      i {
        margin-right: 5px;
      }
    }
  }
}
</style>

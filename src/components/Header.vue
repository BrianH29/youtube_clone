<template>
  <header>
    <div>
      <i class="fab fa-youtube"></i>
      <span>Youtube</span>
    </div>
    <div>
      <i class="fas fa-search"></i>
      <i class="fas fa-ellipsis-v"></i>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
header {
  display: flex;
  justify-content: space-between;
  color: map-get($font-color, 'white');
  padding: 12px;

  :nth-child(1) {
    i {
      color: map-get($font-color, 'red');
      margin-right: 2px;
    }

    span {
      font-weight: 600;
    }
  }

  :nth-child(2) {
    .fa-search {
      margin-right: map-get($font-space, 'spacing');
    }
  }
}
</style>

<template>
  <section class="video__title">
    <span>
      Golden State Warriors vs Houston Rockets Full Game Highlights | 2021-22
      NBA Season
    </span>
    <button>
      <i class="fas fa-caret-down"></i>
    </button>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.video__title {
  display: flex;
  background: map-get($font-color, 'black');
  padding: 0 12px;

  span {
    color: map-get($font-color, 'white');
    font-size: map-get($font-size, 'regular');
    font-weight: 500;
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 2;
    overflow: hidden;
  }

  button {
    background: map-get($font-color, 'black');
    padding: 0 5px;
    align-self: baseline;

    i {
      color: map-get($font-color, 'white');
    }
  }
}
</style>

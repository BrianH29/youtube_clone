<template>
  <div class="video__title">
    <span>
      Golden State Warriors vs Houston Rockets Full Game Highlights | 2021-22
      NBA Season
      <!--      Clone Coding: Youtube Mobile Website 유튜브 모바일 웹사이트 따라 만들기 |-->
      <!--      프론트엔드 개발자 입문편: HTML, CSS, Javascript 드림코딩과 함께하는-->
      <!--      프론트엔드 실전 입문편-->
    </span>
    <button>
      <i class="fas fa-caret-down"></i>
    </button>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.video__title {
  display: flex;
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

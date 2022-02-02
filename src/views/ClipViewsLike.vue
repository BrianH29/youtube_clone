<template>
  <div class="wrapper">
    <ViewCount class="wrapper__viewCount"></ViewCount>
    <LikeActionBtn class="wrapper__actionBtn"></LikeActionBtn>
  </div>
</template>

<script>
import ViewCount from '@/components/ViewCount';
import LikeActionBtn from '@/components/LikeActionBtn';

export default {
  components: { LikeActionBtn, ViewCount },
};
</script>

<style lang="scss" scoped>
.wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: map-get($font-space, 'spacing');
  background: map-get($font-color, 'black');

  #{&}__viewCount {
    margin-right: map-get($font-space, 'spacing');
  }
}
</style>

<template>
  <section class="infoAndUpNext">
    <div>
      <HashTag></HashTag>
      <VideoTitle></VideoTitle>
      <ClipViewsLike></ClipViewsLike>
      <BorderGradient></BorderGradient>
      <UserInfo></UserInfo>
      <BorderGradient></BorderGradient>
    </div>
    <div>
      <ThumbNailView></ThumbNailView>
    </div>
  </section>
</template>

<script>
import UserInfo from '@/components/UserInfo';
import ThumbNailView from '@/components/ThumbNailView';
import HashTag from '@/components/HashTag';
import VideoTitle from '@/components/VideoTitle';
import ClipViewsLike from '@/views/ClipViewsLike';
import BorderGradient from '@/components/BorderGradient';

export default {
  components: {
    BorderGradient,
    ClipViewsLike,
    VideoTitle,
    HashTag,
    ThumbNailView,
    UserInfo,
  },
};
</script>

<style lang="scss" scoped>
.infoAndUpNext {
  display: flex;
  flex-direction: column;
}

@media screen and (min-width: 768px) {
  .infoAndUpNext {
    flex-direction: row;
  }
}
</style>

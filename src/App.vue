<template>
  <div id="app">
    <Header></Header>
    <ShowVideo></ShowVideo>
    <HashTag></HashTag>
    <VideoTitle></VideoTitle>
    <ClipViewsLike></ClipViewsLike>
    <BorderGradient></BorderGradient>
    <UserInfo></UserInfo>
    <BorderGradient></BorderGradient>
  </div>
</template>

<script>
import Header from '@/components/Header';
import ShowVideo from '@/components/ShowVideo';
import HashTag from '@/components/HashTag';
import VideoTitle from '@/components/VideoTitle';
import ClipViewsLike from '@/views/ClipViewsLike';
import BorderGradient from '@/components/BorderGradient';
import UserInfo from '@/components/UserInfo';
export default {
  components: {
    UserInfo,
    BorderGradient,
    ClipViewsLike,
    VideoTitle,
    HashTag,
    ShowVideo,
    Header,
  },
};
</script>

<style lang="scss">
* {
}
</style>

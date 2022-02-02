<template>
  <div id="app">
    <Header></Header>
    <ShowVideo></ShowVideo>
    <HashTag></HashTag>
    <VideoTitle></VideoTitle>
    <ClipViewsLike></ClipViewsLike>
  </div>
</template>

<script>
import Header from '@/components/Header';
import ShowVideo from '@/components/ShowVideo';
import HashTag from '@/components/HashTag';
import VideoTitle from '@/components/VideoTitle';
import ClipViewsLike from '@/views/ClipViewsLike';
export default {
  components: { ClipViewsLike, VideoTitle, HashTag, ShowVideo, Header },
};
</script>

<style lang="scss">
* {
}
</style>

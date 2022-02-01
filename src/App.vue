<template>
  <div id="app">
    <Header></Header>
    <ShowVideo></ShowVideo>
    <HashTag></HashTag>
    <VideoTitle></VideoTitle>
  </div>
</template>

<script>
import Header from '@/components/Header';
import ShowVideo from '@/components/ShowVideo';
import HashTag from '@/components/HashTag';
import VideoTitle from '@/components/VideoTitle';
export default {
  components: { VideoTitle, HashTag, ShowVideo, Header },
};
</script>

<style lang="scss">
* {
}
</style>

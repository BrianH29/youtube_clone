<template>
  <div id="app">
    <Header></Header>
    <ShowVideo></ShowVideo>
    <UserInfoThumbnailTransform></UserInfoThumbnailTransform>
  </div>
</template>

<script>
import Header from '@/components/Header';
import ShowVideo from '@/components/ShowVideo';
import UserInfoThumbnailTransform from '@/views/UserInfoThumbnailTransform';
export default {
  components: {
    UserInfoThumbnailTransform,
    ShowVideo,
    Header,
  },
};
</script>

<style lang="scss">
* {
}
</style>

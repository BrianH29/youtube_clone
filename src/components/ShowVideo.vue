<template>
  <section class="video_player">
    <video controls src="@/assets/video/testsVideo.mp4"></video>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.video_player {
  position: sticky;
  top: 0;
  background: map-get($font-color, 'black');

  video {
    width: 100%;
  }
}
</style>

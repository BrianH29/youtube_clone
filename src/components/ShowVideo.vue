<template>
  <div class="video_player">
    <video controls src="@/assets/video/testsVideo.mp4"></video>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.video_player {
  position: sticky;
  top: 0;
  background: black;
  text-align: center;

  video {
    width: 100%;
    height: 100%;
    max-height: 400px;
    max-width: 1000px;
  }
}
</style>

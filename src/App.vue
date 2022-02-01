<template>
  <div id="app">
    <Header></Header>
    <ShowVideo></ShowVideo>
  </div>
</template>

<script>
import Header from '@/components/Header';
import ShowVideo from '@/components/ShowVideo';
export default {
  components: { ShowVideo, Header },
};
</script>

<style lang="scss">
* {
}
</style>

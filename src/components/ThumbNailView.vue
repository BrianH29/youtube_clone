<template>
  <section>
    <div v-for="(item, idx) in dataList" :key="idx" class="thumbnail">
      <div class="thumbnail__img">
        <img :src="item.imgUrl" alt="" />
      </div>
      <div class="thumbnail__info">
        <span>{{ item.clipTitle }}</span>
        <span>{{ item.userInfo }}</span>
        <span>{{ item.viewCount }}</span>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      dataList: [
        {
          imgUrl: require('@/assets/img/thumbNail1.png'),
          clipTitle:
            '[육룡이나르샤] 👊무인들의 대격돌👊 무휼 vs 길선미, 척사광 vs 이방지 과연 살아남을 자는 누구인가💥💥💥 | 50화',
          userInfo: '깃 옛날드라마',
          viewCount: '조회수 101만 3개월 전',
        },
        {
          imgUrl: require('@/assets/img/thumbNail2.png'),
          clipTitle:
            '[정주행 용] "너 언니한테 까불면 모가지 날아간다..." 영화 \'마녀\'_ tmi 총정리',
          userInfo: '마녀 옛날드라마',
          viewCount: '조회수 1,234,567회',
        },
        {
          imgUrl: require('@/assets/img/thumbNail3.png'),
          clipTitle:
            '[정주행 용] "너 언니한테 까불면 모가지 날아간다..." 영화 \'마녀\'_ tmi 총정리',
          userInfo: '마녀 옛날드라마',
          viewCount: '조회수 100만 1년전',
        },
        {
          imgUrl: require('@/assets/img/thumbNail4.png'),
          clipTitle:
            '[정주행 용] "너 언니한테 까불면 모가지 날아간다..." 영화 \'마녀\'_ tmi 총정리',
          userInfo: '마녀 옛날드라마',
          viewCount: '조회수 100회' + '',
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.thumbnail {
  display: flex;
  padding: map-get($font-space, 'spacing');

  #{&}__img {
    width: 35%;
    margin-right: 10px;
    img {
      width: 100%;
      height: 100%;
    }
  }

  #{&}__info {
    display: flex;
    flex-direction: column;
    width: 65%;
    color: map-get($font-color, 'white');
  }
}
</style>

<template>
  <div class="video__title">
    <span class="clamp">
      Golden State Warriors vs Houston Rockets Full Game Highlights | 2021-22
      NBA Season
    </span>
    <button @click="moreBtn">
      <i class="fas fa-caret-down"></i>
    </button>
  </div>
</template>

<script>
export default {
  methods: {
    moreBtn() {
      const title = document.querySelector('.video__title span');
      const moreBtn = document.querySelector('button i');

      title.classList.toggle('clamp');
      moreBtn.classList.toggle('clicked');
    },
  },
};
</script>

<style lang="scss" scoped>
.video__title {
  display: flex;
  padding: 0 12px;

  span {
    color: map-get($font-color, 'white');
    font-size: map-get($font-size, 'regular');
    font-weight: 500;
  }

  span.clamp {
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 2;
    overflow: hidden;
  }

  button {
    background: map-get($font-color, 'black');
    padding: 0 5px;
    align-self: baseline;

    i {
      color: map-get($font-color, 'white');
      transition: transform 300ms ease-in-out;
    }

    i.clicked {
      transform: rotate(180deg);
    }
  }
}
</style>

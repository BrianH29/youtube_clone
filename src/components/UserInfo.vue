<template>
  <div class="userInfo_wrapper">
    <section class="userInfo">
      <div class="userInfo__img">
        <img src="@/assets/img/lisa.jpeg" alt="" />
      </div>
      <div class="userInfo__name">
        <ul>
          <li>코미디심슨 by 리사</li>
          <li>구독자 1.5천명</li>
        </ul>
      </div>
    </section>
    <section class="subscribe">
      <div class="subscribe__btn">
        <button>구독</button>
      </div>
      <div class="subscribe__alarm">
        <i class="far fa-bell"></i>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.userInfo_wrapper {
  display: flex;
  justify-content: space-between;
  padding: map-get($font-space, 'spacing');
  align-items: center;
}

.userInfo {
  display: flex;
  color: map-get($font-color, 'white');

  #{&}__img {
    img {
      border-radius: 50%;
      margin-right: 12px;
      width: map-get($avatar-size, 'size');
      height: map-get($avatar-size, 'size');
    }
  }

  #{&}__name {
    ul {
      display: flex;
      flex-direction: column;
      list-style: none;

      :first-child {
        font-size: map-get($font-size, 'regular');
      }

      :nth-child(2) {
        font-size: map-get($font-size, 'small');
        color: map-get($font-color, 'darkGrey');
      }
    }
  }
}

.subscribe {
  display: flex;
  align-items: center;

  #{&}__btn {
    margin-right: map-get($font-space, 'spacing');
    button {
      background: map-get($font-color, 'red');
      color: map-get($font-color, 'white');
      font-size: map-get($font-size, 'regular');
      width: 4.5em;
      height: 2.3em;
      letter-spacing: 1.2px;
    }
  }

  #{&}__alarm {
    color: map-get($font-color, 'white');
    font-size: 25px;
  }
}
</style>

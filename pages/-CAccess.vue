<template>
  <section class="c-accsess">
      <div class="c-accsess__container">
        <div class="c-accsess__map"></div>
      <div class="c-accsess__title">
          <p>Access</p>
          <p class="c-accsess__subtitle">アクセス</p>
          <div class="c-accsess__addr">
            <p>くるみどり<br>
            東京都世田谷区世田谷1丁目29-14</p>
          </div>
          <div class="c-accsess__train">
            <p class="c-accsess__mdr">●電車でお越しのお客様</p>
            <p class="c-accsess__kr">東急世田谷線 上町駅から徒歩7分</p>
            <p class="c-accsess__mdr">●車でお越しのお客様</p>
            <p class="c-accsess__kr">東駐車場無し / コインパーキング複数有り</p>
          </div>
      </div>
      </div>
 </section>
</template>

<script>
  export default {
  }
</script>

<style lang="scss" scoped>
@import "~assets/scss/mixins.scss";
.c-accsess {
margin: 40px 15px 20px;

  &__map {
    width: 274px;
    height: 274px;
    background: skyblue;
    margin: 10px auto;
  }

  &__title {
    text-align: center;
    font-size: 30px;

    @include mobile {
      font-size: 24px;
      margin-bottom: 40px;
    }
  }

  &__subtitle {
    margin-bottom: 40px;
  }

  &__addr {
    font-size: 15px;
    margin-bottom: 40px;
    text-align: left;
  }

  &__train {
    font-size: 15px;
    text-align: left;
    display: block;
  }

  &__mdr {
    color: #2d704b;
    margin-bottom: 8px;
  }

  &__kr {
    margin-bottom: 24px;
  }
}

</style>
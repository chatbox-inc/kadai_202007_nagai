<template>
  <section class="c-accsess">
      <div class="c-accsess__container">
        <div class="c-accsess__box">
        <div class="c-accsess__map"></div>
      <div class="c-accsess__ass">
        <div class="c-accsess__title">
          <p>Access</p>
        </div>
          <p class="c-accsess__text">アクセス</p>
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
      </div>
      <div class="c-accsess__box1">
        <div class="c-accsess__tel">
        <p class="c-accsess__number">03-6319-6455</p>
        <p class="c-accsess__time">営業時間/10:00-17:00<br>
        定休日/月・木</p>
        </div>
        <div class="c-accsess__inf">
            <p>お問い合わせフォーム</p>
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
  background: #F3F8F6;

  &__container {
margin: 40px 15px 20px;
  }

&__ass {
  margin: 0 auto;
}

&__box {
  display: flex;
  flex-flow: row-reverse;

  @include mobile {
    display: block;
  }
}

  &__map {
    width: 100%;
    max-width: 543px;
    max-height: 430px;
    background: skyblue;

    @include mobile {
    width: 274px;
    height: 274px;
    margin: 10px auto;
    }
  }

  &__title {
    font-size: 40px;
    text-align: left;
    margin-bottom: 64px;
    color: #2C714B;

    @include mobile {
      margin-bottom: 40px;
    }
  }

  &__text {
    font-size: 15px;
    margin-bottom: 100px;

    @include mobile {
    margin-bottom: 60px;
    }
  }

  &__addr {
    font-size: 15px;
    margin-bottom: 40px;
    text-align: left;
    color: #433533;
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
    color: #433533;
  }

  &__tel {
    width: 100%;
    padding: 20px 4% 32px;
      background: #fff;
      text-align:center;
      line-height: 50px;
      text-align: center;
      margin: 0 auto;

      @include mobile {
      width: 100%;
      }
  }

  &__number {
    font-size: 34px;
    color:#2d704b;
  }

  &__time {
    font-size: 13px;
  }

  &__box1 {
    display: flex;

    @include mobile {
      display: block;
    }
  }

  &__inf {
    width: 100%;
    padding: 40px 4% 32px;
      background: #2d704b;
      color: #fff;
      font-size: 22px;
      text-align:center;
      line-height: 50px;
      text-align: center;
      margin: 0 auto;

      @include mobile {
      width: 100%;
      }

      &__last {
        bottom: 0;
      }
  }
}

</style>
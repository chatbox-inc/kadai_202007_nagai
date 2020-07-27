<template>
  <section class="c-news">
      <div class="c-news__container">
        <div class="c-news__foto">
          <img class="c-news__caf"
            src="@/assets/image/heya.jpg"
                alt="花を楽しむ"/>
        </div>
        <div class="c-news__box">
          <div class="c-news__box1">
      <div class="c-news__title">
          <h1>NEWS</h1>
          <p class="c-news__text">お知らせ</p>
      </div>
        </div>
        <div class="c-news__box2">
          <p>
            <span class="c-news__day">
              2020.09,09</span><br>
              <span class="c-news__ivnt">
                セット販売も承ります♪</span></p>
                <hr size="5">
                <span class="c-news__day">
              2020.09,09</span><br>
              <span class="c-news__ivnt">
                セット販売も承ります♪</span></p>
                <hr size="5">
                <span class="c-news__day">
              2020.09,09</span><br>
              <span class="c-news__ivnt">
                セット販売も承ります♪</span></p>
                <hr size="5">
                <p class="c-news__greenb" href="~">MORE</p>
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

.c-news {

  &__container {
    @include mobile {
    padding:40px 4% 60px;
    }
  }
&__title {
    font-size: 40px;
    text-align: center;
    margin-bottom: 64px;
    color: #2C714B;

    @include mobile {
      margin-bottom: 40px;
    }
  }

  &__text {
    font-size: 15px;
    margin-bottom: 100px;
    color: #433533;

    @include mobile {
    margin-bottom: 60px;
    }
  }

  &__box {
    display: flex;
    background: #FFF;
    width: 50%;
    position: relative;
    top: -150px;
    padding: 100px 6%;
    @include mobile {
      display: block;
      width: 100%;
      top: 0;
      padding: 0;
  }
}

&__box1 {
  padding-right: 80px;

  @include mobile {
    padding-right: 0;

}
}

&__day {
  font-size: 13px;
  color: #2C714B;
}

&__ivnt {
  font-size: 15px;
}

&__greenb {
      position: relative;
      width: 240px;
      height: 50px;
      background: #f4f8f7;
      text-align:center;
      font-size: 15px;
      color: #2d704b;
      line-height: 50px;
      text-align: center;
      margin: 0 auto;

      @include mobile {
      width: 70%;
      bottom: -20px;
      right: 0;
      left: 0;
      }
    }
}
</style>

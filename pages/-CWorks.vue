<template>
  <section class="c-works">
      <div class="c-works__container">
      <div class="c-works__title">
          <p>works</p>
          <p class="c-works__text">空間デザイン施工事例</p>
      </div>
        <div class="c-works__box">
        <div class="c-works__btn">
          <a class="c-works__hana" 
          href="#">
          <img class="c-works__hana"
            src="@/assets/image/hana.jpg"
                alt="花を楽しむ"/>
          <div class="c-works__next">
             <p class="c-works__next1">ウェディング　デザイン装飾</p>
          </div>
          </a>
        </div>
        <div class="c-works__btn">
          <a class="c-works__hana" 
          href="#">
          <img class="c-works__hana"
            src="@/assets/image/hana.jpg"
                alt="花を楽しむ"/>
          <div class="c-works__next">
             <p class="c-works__next1">音楽フェス　デザイン装飾</p>
          </div>
          </a>
        </div>
        </div>
        <p class="c-works__button" href="~">施工実績一覧</p>
      </div>
 </section>
</template>

<script>
  export default {
  }
</script>

<style lang="scss" scoped>
@import "~assets/scss/mixins.scss";
 .c-works {
   background: #F3F8F6;
   
     width: 100%;
     padding-bottom: 100px;
     @include mobile {
     padding: 0 15px 100px;
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

    @include mobile {
    margin-bottom: 60px;
    }
  }

  &__box {
    display: flex;
    justify-content: space-evenly;
    margin-bottom: 100px;

    @include mobile {
      margin-bottom: 50px;
    }
  }

  &__btn {
  display: block;
  margin: 0 auto;
  }

  &__hana {
    max-width: 275px;
    height: auto;

    @include mobile {
    width: 100%;
    }
  }

  &__next {
    position: relative;
    background: #fff;
    text-align:center;
    font-size: 16px;
    padding: 24px 24px 40px 24px;
    max-width: 275px;
    height: auto;

    @include mobile {
    padding: 16px 8% 24px;
    width: 100%;
    font-size: 15px;
    top: 0;
    line-height: 18px;
    }
  }

  &__next1 {  
     font-size: 16px;
     text-align:left;

     @include mobile {
       font-size: 15px;
     }
  }

  &__button {
      position: relative;
      width: 350px;
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
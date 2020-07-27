<template>
  <section class="c-hero">
      <div class="c-hero__container">
        <div class="c-hero__box">
            <div class="c-hero__top">
              <img class="c-hero__cafe"
              src="@/assets/image/cafe.jpg"
              alt="カフェ"/>
              <p class="c-hero__btn">CAFE</p>
              <p class="c-hero__subbtn">カフェ</p>
            </div>
            <div class="c-hero__top">
              <img class="c-hero__cafe"
              src="@/assets/image/cafe_.jpg"
              alt="カフェ"/>
              <p class="c-hero__btn">PLA</p>
              <p class="c-hero__subbtn">インテリアグリーン</p>
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

 .c-hero {
   &__container {
     margin: 0 35px;
     padding-bottom: 160px;
   }

   &__box {
     display: flex;
     align-items: center;
     
     @include mobile {
       display: block;
    }
   }

   &__top {
     width: 50%;
    background: rgb(109, 109, 109);
    margin: 10px auto;
    text-align: center;
    color: #fff;

  @include mobile {

    width: 100%;
    background: rgb(109, 109, 109);
    margin: 10px auto;
    text-align: center;
    color: #fff;
   }
  }

  &____btn {
    font-size: 60px;
  }
 }

</style>

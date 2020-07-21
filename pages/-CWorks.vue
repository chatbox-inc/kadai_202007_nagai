<template>
  <section class="c-works">
      <div class="c-works__container">
      <div class="c-works__title">
          <p>works</p>
          <p class="c-works__subtitle">空間デザイン施工事例</p>
      </div>
        <div class="c-works__box">
            <div class="c-works__box01">
            </div>
        <div class="c-works__menue">
        <a class="c-works__hana" href="~">花を楽しむ</a><br>
        <a class="c-works__hana" href="~">緑を楽しむ</a>
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
 .c-works {
     width: 100%;

   &__title {
    font-size: 40px;
    padding-bottom: 15px;
    color: #2C704A;
    text-align:center;
    
  }

    &__menue {
      display: inline-flex;

      @include mobile {
        display: block;
      }
  }


  &__hana {
  margin: 0 30px;
  margin-left: auto;
  margin-right: auto;
  width: 40%;
  height: 300px;
  background: rgb(109, 109, 109);
  text-align:center;
  font-size: 100px;
  color: #fff;
  line-height: 160px;

  @include mobile {
    margin: 0;
    height: 300px;
    width: 300px;
    font-size: 30px;
    line-height: 300px;
    margin-bottom: 100px;
      line-height: 300px;
      
  }
  }
 }
 </style>
<template>
  <section class="c-sns">
      <div class="c-sns__container">
      <div class="c-sns__title">
          <p>Instagram</p>
      </div>
      <div class="c-sns__url">
        <p>kurumidori</p>
      </div>
       <div class="c-sns__box">
      <div class="c-sns__box1">
      <div class="c-sns__ist"></div>
      <div class="c-sns__ist"></div>
      <div class="c-sns__ist"></div>
      <div class="c-sns__ist"></div>
      </div>
      <div class="c-sns__box2">
      <div class="c-sns__ist"></div>
      <div class="c-sns__ist"></div>
      <div class="c-sns__ist"></div>
      <div class="c-sns__ist"></div>
      </div>
       </div>
      <div class="c-sns__button">
        <a class="c-sns__more" href="">Read More ...</a>
        <a class="c-sns__follow" href="">Follow in Instagram</a>
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

.c-sns {
  margin-bottom: 60px;

  &__title{
    text-align: center;
    font-size: 30px;

    @include mobile {
      font-size: 24px;
      margin-bottom: 40px;
    }
  }

  &__url {
    font-size: 16px;
    margin-bottom: 30px;
  }

  &__ist {
    width: 274px;
    height: 274px;
    background: skyblue;
    margin: 10px auto;
  }

  &__button {
    margin: 30px auto 10px;
  }

  &__more {
    padding: 7px 14px;
    background: rgb(78, 60, 35);
    border-radius: 30%;
    color: #fff;
    box-sizing: border-box;
  }

  &__follow {
    padding: 7px 14px;
    background: rgb(62, 148, 40);
    border-radius: 30%;
    color: #fff;
  }

  &__box {
    padding: 5px;
    text-align:center;
  }
  &__box1 {
    display: inline-flex;
    justify-content: center;

    @include mobile {
      display: inline-block;
    }
  }

  &__box2 {
    display: inline-flex;
    justify-content: center;
    margin: 0 auto;

    @include mobile {
      display: inline-block;
    }
  }

  &__ist {
    margin: 5px;
  }
}

</style>
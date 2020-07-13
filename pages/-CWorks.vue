<template>
  <section class="c-works">
      <div class="c-works__container">
      <div class="c-works__title">
          <h1>works</h1>
          <p class="c-works__subtitle">空間デザイン施工事例</p>
      </div>
        <div class="c-works__box">
            <div class="c-works__box01">
            </div>
        <div class="c-works__menue">
        <a class="c-works__hana" href="~">花を楽しむ</a>
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
  }
 }
 </style>
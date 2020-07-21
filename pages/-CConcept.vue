<template>
  <section class="c-concept">
    <div class="head">
    <div class="top"> 


        <div class="c-concept__title">
            <h1>CONSEPT</h1>
        </div>
        <div class="c-concept__subtitle">
            <p>食べるお花と彩る緑</p>
         </div>
    </div>
    <div class="c-concept__text">
        私たちは、食べて癒やされ、見て楽しんでいただくボタニカルカフェです。<br>
        お花を使ったスイーツやハーブティーはもちろんのこと、生活を彩る厳選した1点物の植物をご購入いただけます。<br>
        そして家の中と外をつなぐ、新たな居住空間をグリーンプロデュースをいたします
    </div>
    </div>
    <div class="c-concept__box">
    <div class="c-concept__menue">
        <img class="c-concept__hana"
        src="@/assets/image/hana.jpg"
              alt="花を楽しむ">
        <img class="c-concept__hana"
        src="@/assets/image/kanyou.jpg"
              alt="緑を楽しむ">
        <img class="c-concept__hana"
        src="@/assets/image/heya.jpg"
              alt="空間を楽しむ">       
    </div>
    <div class="c-concept__nextb">
    <div class="c-concept__next">CAFE</div>
    <div class="c-concept__next">PLANTS</div>
    <div class="c-concept__next">CREEN DEZING</div>
    </div>
    </div>

   <div class="c-concept__box01">
     <div class="c-concept__box00">
     <p class="c-concept__nunber">01</p>
       <p class="c-concept__section"> CAFFE<br>
         カフェ</p>
         <p class="c-concept__title2"> コーヒーやお菓子を、<br>
         植物に囲まれた空間で。</p>
         <p class="c-concept__text1">
           食べられるお花はひとつひとつ形も違い、スイーツやクッキーは手作り。 パティシエが作る、世界にひとつだけの特別なスイーツです。
季節限定のデザートや、お花杏仁は限定でご提供させていただいております。
         </p>
         <a class="c-concept__greenb" href="~">MORE</a>
     </div>
       <div class="c-concept__foto"></div>
       </div>

  </section>
</template>

<script>
  export default {
  }
</script>

<style lang="scss" scoped>
@import "~assets/scss/mixins.scss";



.c-concept {
  width: 100%;
  text-align: center;

  &__title {
    font-size: 40px;
    padding-bottom: 15px;
    color: #2C704A;

    @include mobile {
    }
  }

  &__subtitle {
    font-size: 18px;
    padding-bottom: 30px;
  }

  &__text {
      padding-bottom: 30px;
  }

  &__menue {
      display: inline-flex;

      @include mobile {
        display: inline-block;
      }
  }

  &__hana {
  margin: 0 30px;
  margin-left: auto;
  margin-right: auto;
  width: 30%;
  height: 560px;
  background: rgb(109, 109, 109);
  text-align:center;
  font-size: 100px;
  color: #fff;
  line-height: 160px;

  @include mobile {
    display: inline-block;
    height: 300px;
    width: 300px;
    font-size: 30px;
    line-height: 300px;
    margin-bottom: 100px;
  }

  }


&__nextb {
    display: inline-flex;
    margin-left: auto;
    margin-right: auto;

    @include mobile {
      display: block;
      position: absolute;
      bottom: -280px;
      right: 0;
      left: 0;
      margin: 100px auto;
      text-align: center;
      color: #fff;
    }
}

&__next {
  margin: -25px 180px;
  width: 25%;
  height: 50px;
  background: rgb(255, 228, 228);
  text-align:center;
  font-size: 30px;
  color: #fff;
  line-height: 50px;

  @include mobile {
    font-size: 20px;
    margin: 0 auto;
    width: 210px;
    height: 50px;
    top: 0;

  }
  
  }

  &__box {
  padding-bottom: 150px;
  }

&__box01 {
  display: inline-flex;
  max-width: 100%;

  @include mobile {
    display: inline-block;
  }
  }

  &__box01 {
    width: 300px;
    height: 500px;
    background: #fff;
  }

  &__foto {
    margin-left: 30px;
    margin-right: 0;
    width: 600px;
    height: 500px;
    background: rgb(109, 109, 109);

    @include mobile {
      margin: 0;
      left: 0;
      width: 288px;
      height: 190px;
      padding-bottom: 100px;
    }
  }

  &__greenb {
     display: inline-block;
  width: 80px;
  height: 40px;
  background: skyblue;
  text-align:center;
  line-height: 80px;


  @include mobile {
  margin: 30px 0;
  line-height: 40px;
  }
  }

}
</style>
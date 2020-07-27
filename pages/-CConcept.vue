<template>
  <section class="c-concept">
    <div class="c-concept__container">
      <div class="c-concept__top">
        <div class="c-concept__title">
          <p>CONCEPT</p>
        </div>
        <div class="c-concept__text">
        <p>私たちは、食べて癒やされ、見て楽しんでいただくボタニカルカフェです。<br>
        お花を使ったスイーツやハーブティーはもちろんのこと、生活を彩る厳選した1点物の植物をご購入いただけます。<br>
        そして家の中と外をつなぐ、新たな居住空間をグリーンプロデュースをいたします</p>
        </div>
      </div>
      <div class="c-concept__area">
        <div class="c-concept__caffe">
          <a class="c-concept__hana" 
          href="#">
          <img class="c-concept__hana"
            src="@/assets/image/hana.jpg"
                alt="花を楽しむ"/>
          <p class="c-concept__next">CAFE</p>
          </a>
        </div>
        <div class="c-concept__prant">
          <a class="c-concept__hana" 
          href="#">
          <img class="c-concept__hana"
            src="@/assets/image/kanyou.jpg"
                alt="緑を楽しむ"/>
          <p class="c-concept__next">
                    PLANTS
          </p>
          </a>
        </div>
        <div class="c-concept__design">
          <a class="c-concept__hana" 
          href="#">
          <img class="c-concept__hana"
            src="@/assets/image/heya.jpg"
                alt="部屋を楽しむ"/>
                  <p class="c-concept__next">
                    GREEN DESIIGN
                  </p>
          </a>
        </div>
      </div>
 <div class="c-concept__svs">
    <div class="c-concept__foto">
         <img class="c-concept__caf"
            src="@/assets/image/heya.jpg"
                alt="花を楽しむ"/>
       </div>
    <div class="c-concept__txt">
     <div class="c-concept__box">
     <p class="c-concept__nunber">(01)</p>
       <p>
        <span class="c-concept__section"> CAFFE</span><br>
         <span class="c-concept__section1">カフェ</span>
         </p>
         <p class="c-concept__title2"> コーヒーやお菓子を、<br>
         植物に囲まれた空間で。</p>
         <p class="c-concept__text1">
           食べられるお花はひとつひとつ形も違い、スイーツやクッキーは手作り。 パティシエが作る、世界にひとつだけの特別なスイーツです。 <br>
季節限定のデザートや、お花杏仁は限定でご提供させていただいております。
         </p>
         <p class="c-concept__greenb" href="~">MORE</p>
     </div>
      </div>
    </div>
    
    <div class="c-concept__svs1">
    <div class="c-concept__foto">
         <img class="c-concept__caf"
            src="@/assets/image/heya.jpg"
                alt="花を楽しむ"/>
       </div>
    <div class="c-concept__txt">
     <div class="c-concept__box">
     <p class="c-concept__nunber">(02)</p>
       <p>
        <span class="c-concept__section"> PLANTS</span><br>
         <span class="c-concept__section1">インテリアグリーン</span>
         </p>
         <p class="c-concept__title2"> 植物を置くことによって<br>
         日々の生活に彩りを。</p>
         <p class="c-concept__text1">
           季節ごとに葉を生い茂らせ、花を咲かせ、実をつけ、紅葉し落葉する。 <br>
           インテリアを彩ってくれるのはもちろんのことですが、人の生活に癒やしを与えてくれます。<br>
           1点物の植物との出会いをお楽しみください
         </p>
         <p class="c-concept__greenb" href="~">MORE</p>
     </div>
      </div>
    </div>

    <div class="c-concept__svs">
    <div class="c-concept__foto">
         <img class="c-concept__caf"
            src="@/assets/image/heya.jpg"
                alt="花を楽しむ"/>
       </div>
    <div class="c-concept__txt">
     <div class="c-concept__box">
     <p class="c-concept__nunber">(03)</p>
       <p>
        <span class="c-concept__section"> GREEN<br>DESIGN</span><br>
         <span class="c-concept__section1">カフェ</span>
         </p>
         <p class="c-concept__title2"> コーヒーやお菓子を、<br>
         植物に囲まれた空間で。</p>
         <p class="c-concept__text1">
           食べられるお花はひとつひとつ形も違い、スイーツやクッキーは手作り。 パティシエが作る、世界にひとつだけの特別なスイーツです。 <br>
季節限定のデザートや、お花杏仁は限定でご提供させていただいております。
         </p>
     </div>
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

.c-concept {
  width: 100%;
  text-align: center;

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

  &__area {
    width: 100%;
    padding: 0 3% 180px;
    margin-top: 120px;
    display: flex;
    justify-content: space-between;
    position: relative;

    @include mobile {
      margin: 0 auto;
    display: block;
    }
  }

    &__caffe {
      display: block;
      width: auto;
      height: 100%;
      position: relative;
      margin: 0 15px;

      @include mobile {
        display: block;
        width: auto;
        height: 100%;
        position: relative;
        margin-bottom: 100px;
      }
    }

    &__prant {
      display: block;
      width: auto;
      height: 100%;
      position: relative;
      margin: 0 15px;

      @include mobile {
        display: block;
        width: auto;
        height: 100%;
        position: relative;
        margin-bottom: 100px;
      }
    }

    &__design {
      display: block;
      width: auto;
      height: 100%;
      position: relative;
      margin: 0 15px;

      @include mobile {
        display: block;
        width: auto;
        height: 100%;
        position: relative;
        margin-bottom: 100px;
      }
    }

    &__next {
      position: relative;
      width: 25%;
      height: 50px;
      background: rgb(78, 60, 35);
      text-align:center;
      font-size: 20px;
      color: #fff;
      line-height: 50px;
      text-align: center;
      margin: 0 auto;

      @include mobile {
      position: absolute;
      width: 70%;
      bottom: -20px;
      right: 0;
      left: 0;
      }
    }

    &__btn {
      position: relative;
      width: 25%;
      height: 50px;
      text-align:center;
      font-size: 30px;
      background-color: #000;
      line-height: 50px;
      text-align: center;
      margin: 0 auto;

      @include mobile {
      position: absolute;
      width: 70%;
      bottom: -170px;
      right: 0;
      left: 0;
      }
    }

    &__nunber {
      font-size: 50px;
      padding-bottom: 30px;
    }

    &__section {
      font-size: 52px;
      color: #2C714B;
      margin-top: 24px;

      @include mobile {
        margin-top: 8px;
      }
    }

    &__section1 {
      font-size: 15px;
      color: #2C714B;
    }

    &__title2 {
      font-size: 24px;
      margin: 60px 0 30px;
      color: #433533;
    }

    &__text1 {
      color: #433533;
      padding-bottom: 60px;
      @include mobile {
        max-width: 100%;
        text-align: left;
      }
    }

    &__svs {
      display: flex;
      flex-flow: row-reverse;
      margin-top: 80px;

      @include mobile {
        display: block;
        margin-top: 0;
      }
    }

    &__svs1 {
      display: flex;
      margin-top: 80px;

      @include mobile {
        display: block;
        margin-top: 0;
      }
    }


    &__box {
      width: 85%;
      min-width: 620px;
      margin-left: auto;
      padding: 30px 100px 0;
      text-align: center;

      @include mobile {
        min-width: 320px;
        margin-left: none;
        padding: 30px 15px 70px;
      }
    }

    &caf {
      width: 100%;
      min-width: 600px;
      max-width: 100%;
      height: auto;
      border: none;
      vertical-align: bottom;

      @include mobile {
        width: 90%;
        min-width: inherit;
        max-width: 100%;
      }
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
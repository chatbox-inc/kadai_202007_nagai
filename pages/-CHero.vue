<template>
  <section class="c-hero">
      <div class="c-hero__container">
        <div class="c-hero__box">
            <div class="c-hero__site-heading">
              <h1>CAFE</h1>
              <span class="subheading">カフェ</span>
            </div>

            <div class="c-hero__site-heading">
              <h1>PLA</h1>
              <span class="subheading">インテリアグリーン</span>
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
 .c-hero {
   &__box {
     display: inline-flex;
     margin:5% 20%;
     
     @mixin mobile {
       display: none;
       margin: none;
   }
   }

    &__site-heading {
    margin: 0 30px;
    width: 40%;
    text-align:center;
    margin:0 auto;
    height: 560px;
    background: rgb(109, 109, 109);
    font-size: 100px;
    color: #fff;
    line-height: 100px;
    
    @mixin mobile {
       width: 300px;
       height: 200px;
       margin: none;
       font-size: 30px;
   }
  }
  }

</style>
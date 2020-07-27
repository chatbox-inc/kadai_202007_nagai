<template>
  <footer class="l-footer">
    <div class="l-footer__contact">
        <div class="l-footer__link">
            <a class="l-footer__button1"></a>
            <a class="l-footer__button2"></a>
        </div>
        <img class="l-footer__foto"
            src="@/assets/image/kanyou.jpg"
                alt="緑を楽しむ"/>
        <div class="l-footer__last">
            <p>Copyright © KURUMIDORI. All Rights Reserved.</p>
        </div>
        </div>
        </footer>
</template>

<script>
  export default {
  }
</script>

<style lang="scss" scoped>
@import "~assets/scss/mixins.scss";
.l-footer{
&__foto {
  padding-bottom: 100px;
}
  &__last {
    font-size: 10px;
  }
}

</style>
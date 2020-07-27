<template>
  <header class="l-header">
    <div class="l-header__contact">
        <div class="l-header__box">
        <div class="l-header__kurumidori">
        <img class="l-header__logo"
            src="@/assets/image/logo.svg"
                alt="くるみどり"/>
        </div>
        <div class="l-header__day">
            <p>営業時間0:00-17:00<br>
            定休日/月・木</p>
        </div>
        </div>
    </div>
</header>
</template>


<script>
export default {}
</script>

<style lang="scss" scoped>
.l-header {
    width: 100%;
    clear: both;
    background: #fff;
    height: 110px;

    &__box {
        display: inline-flex;
    }
    
    &__logo {
     width: 80px;
     max-width: 100%;
     height: auto;
     padding: 24px 7%;
     background: #fff;
     top: 0;
     left: 0;
    }

   &__day {
    font-size: 11px;

}
}

</style>
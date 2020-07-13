<template>
  <div class="p-index">
    <CHero class="p-index__item" />
    <CConcept class="p-index__item" />
    <CWorks class="p-index__item" />
    <CNews class="p-index__item" />
    <CSns class="p-index__item" />
    <CAccess class="p-index__item" />
  </div>
</template>

<script>
import CHero from '@/pages/-CHero'
import CConcept from '@/pages/-CConcept'
import CWorks from '@/pages/-CWorks'
import CNews from '@/pages/-CNews'
import CSns from '@/pages/-CSns'
import CAccess from '@/pages/-CAccess'

export default {
  components: {
    CHero,
    CConcept,
    CWorks,
    CNews,
    CSns,
    CAccess,
  },
}
</script>

<style lang="scss" scoped>
.p-index {
  &__item {
    &:nth-child(odd) {
      background-color: #faf7f7;
    }
  }
}
</style>

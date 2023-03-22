<template>
  <span>LOL {{t('test')}}</span>
</template>

<script setup lang="ts">
import { useI18n } from 'vue-i18n'

const { locale, t } = useI18n({
  inheritLocale: true
});

</script>


<i18n lang="yaml">
en:
  test: Whats up
de:
  test: Was geht
</i18n>
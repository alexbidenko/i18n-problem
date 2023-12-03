<script lang="ts" setup>
const {t} = useI18n();
</script>

<template>
  <span>{{ t('lang') }}</span>
</template>

<i18n locale="en">
{
  "lang": "English"
}
</i18n>

<i18n locale="de">
{
  "lang": "Deutsch"
}
</i18n>

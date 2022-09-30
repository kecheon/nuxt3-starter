<script lang="ts" setup>
import { capitalize } from '~/utils/str'

// composable
const { t } = useLang()

// compiler macro
definePageMeta({
  layout: 'page',
})
useHead(() => ({
  title: capitalize(t('pages.exs.title')),
  meta: [
    {
      name: 'description',
      content: t('pages.exs.description'),
    },
  ],
}))
</script>

<template>
  <PageContentRenderer path="/exchanges" :page-title="$t('exchanges.title')" />
</template>

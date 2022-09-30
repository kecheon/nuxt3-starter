<script lang="ts" setup>
definePageMeta({
  layout: 'exchanges',
})
</script>

<template>
  <PageWrapper>
    <PageHeader>
      <PageTitle :text="$t('pages.exchanges.index.title')" class="capitalize" />
    </PageHeader>
    <PageBody>
      <PageSection>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia autem
          debitis ab dolorum tempore placeat possimus perferendis porro sit aut
          nobis quasi hic consequuntur, atque impedit nihil totam illo odit?
        </p>
      </PageSection>
      <PageSection>
        <div v-for="i in 10" :key="i" class="text-6xl uppercase">
          {{ $t('pages.blank.just_blank_page_with_title') }}
        </div>
      </PageSection>
    </PageBody>
  </PageWrapper>
</template>

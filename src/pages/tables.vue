<script setup lang="ts">
import DemoSimpleTableBasics from '@/features/tablesDemo/components/DemoSimpleTableBasics.vue'
import DemoSimpleTableDensity from '@/features/tablesDemo/components/DemoSimpleTableDensity.vue'
import DemoSimpleTableFixedHeader from '@/features/tablesDemo/components/DemoSimpleTableFixedHeader.vue'
import DemoSimpleTableHeight from '@/features/tablesDemo/components/DemoSimpleTableHeight.vue'
import DemoSimpleTableTheme from '@/features/tablesDemo/components/DemoSimpleTableTheme.vue'
</script>

<template>
  <VRow>
    <VCol cols="12">
      <VCard title="Basic">
        <DemoSimpleTableBasics />
      </VCard>
    </VCol>

    <VCol cols="12">
      <VCard title="Theme">
        <VCardText>
          use <code>theme</code> prop to switch table to the dark theme.
        </VCardText>
        <DemoSimpleTableTheme />
      </VCard>
    </VCol>

    <VCol cols="12">
      <VCard title="Density">
        <VCardText>
          You can show a dense version of the table by using the <code>density</code> prop.
        </VCardText>
        <DemoSimpleTableDensity />
      </VCard>
    </VCol>

    <VCol cols="12">
      <VCard title="Height">
        <VCardText>
          You can set the height of the table by using the <code>height</code> prop.
        </VCardText>
        <DemoSimpleTableHeight />
      </VCard>
    </VCol>

    <VCol cols="12">
      <VCard title="Fixed Header">
        <VCardText>
          You can fix the header of table by using the <code>fixed-header</code> prop.
        </VCardText>
        <DemoSimpleTableFixedHeader />
      </VCard>
    </VCol>
  </VRow>
</template>

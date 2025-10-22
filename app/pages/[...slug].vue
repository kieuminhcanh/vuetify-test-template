<script lang="ts" setup>
  import * as components from "vuetify/components"
  import * as labs from "vuetify/labs/components"

  const route = useRoute()
  const { data: page } = await useAsyncData(route.path, () => {
    return queryCollection('content').path(route.path).first()
  })

</script>

<template>
  
  <ContentRenderer v-if="page"
    :value="page" 
    :components="{ ...components, ...labs }"
    />

</template>

<style></style>

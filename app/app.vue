<script setup lang="ts">
import { appName } from '~/constants'

useHead({
  title: appName,
})
</script>

<template>
  <VitePwaManifest />
  <UApp>
    <Application>
      <ApplicationHeader />
      <NuxtPage />
    </Application>
  </UApp>
</template>

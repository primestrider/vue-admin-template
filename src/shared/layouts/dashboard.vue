<script setup lang="ts">
import { UDashboardGroup, UDashboardSidebar } from "@/plugins/nuxt-ui/components"
</script>
<template>
  <UDashboardGroup unit="rem" storage="local" storage-key="dashboard_storage">
    <UDashboardSidebar> </UDashboardSidebar>
    <RouterView></RouterView>
  </UDashboardGroup>
</template>

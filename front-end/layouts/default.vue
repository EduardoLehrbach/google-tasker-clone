<template>
  <v-container>
    <add-btn />
    <nuxt />
    <main-navigator />
  </v-container>
</template>

<script>
import MainNavigator from '@/components/navigation/MainNavigator'
import AddBtn from '@/components/navigation/AddBtn'
export default {
  components: { MainNavigator, AddBtn }
}
</script>

<style></style>

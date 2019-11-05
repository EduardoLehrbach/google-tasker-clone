<template>
  <v-container>
    <v-layout>
      <v-flex>
        <h1 class="headline">My Tasks</h1>
        <the-task />
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import TheTask from '@/components/sections/TheTask'
export default {
  components: { TheTask }
}
</script>

<style></style>

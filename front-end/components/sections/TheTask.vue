<template>
  <v-container>
    <v-row>
      <v-col class="col-1">
        <v-btn text icon color="black">
          <v-icon>mdi-record-circle-outline</v-icon>
        </v-btn>
      </v-col>
      <v-col class="d-flex align-center">
        <span class="caption">{{ tasks[0].title }}</span>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'TheTask',
  data() {
    return {
      tasks: [
        {
          id: 0,
          title: 'Terminar componente TheTask'
        }
      ]
    }
  }
}
</script>

<style scoped></style>

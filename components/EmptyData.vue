<template>
  <v-row justify="center" align="center">
    <v-col class="emptyData">
      <v-icon size="200" color="purple">mdi-database</v-icon>
      <p class="title purple--text">Welcome! Select query to get started.</p>
    </v-col>
  </v-row>
</template>
<script>
export default {
  name: 'EmptyData',
}
</script>
<style scoped>
.emptyData {
  text-align: center;
  margin-top: 50px;
}
</style>

<template>
  <div>
    <p>Customer name:</p>
    <v-overflow-btn :items="['USD']" label="Currency"></v-overflow-btn>
    <v-text-field label="Order Description"></v-text-field>
    <v-text-field label="Order Amount" type="number"></v-text-field>
    <v-btn color="success">Confirm</v-btn>
    <v-btn color="error">Cancel</v-btn>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style scoped></style>

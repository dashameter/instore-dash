<template>
  <div>
    <v-simple-table>
      <template v-slot:default>
        <thead>
          <tr>
            <th class="text-left">Date time</th>
            <th class="text-left">Username</th>
            <th class="text-left">Amount</th>
            <th class="text-left">Status</th>
            <th class="text-left">Actions</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Feb 12th, 5:15pm</td>
            <td>Alice</td>
            <td>$5</td>
            <td>Pending</td>
            <td>Amend, Cancel</td>
          </tr>
          <tr>
            <td>Feb 12th, 5:15pm</td>
            <td>Bob</td>
            <td>$3.50</td>
            <td>Paid</td>
            <td>Refund, Amend</td>
          </tr>
          <tr>
            <td>Feb 12th, 5:15pm</td>
            <td>Carol</td>
            <td>$4.50</td>
            <td>Refunded</td>
            <td>Amend</td>
          </tr>
          <tr>
            <td>Feb 12th, 5:15pm</td>
            <td>David</td>
            <td>$4.50</td>
            <td>Cancelled</td>
            <td>-</td>
          </tr>
          <!-- <tr v-for="item in desserts" :key="item.name">
            <td>{{ item.name }}</td>
            <td>{{ item.calories }}</td>
          </tr> -->
        </tbody>
      </template>
    </v-simple-table>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style scoped></style>

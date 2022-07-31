<template>
  <div class="container mt-5">
    <h2>NuxtJS With jQuery DataTables</h2>
    <div class="table-responsive">
      <table id="datatables" class="table table-hover table-striped">
        <thead>
          <tr>
            <th>Name</th>
            <th>Position</th>
            <th>Office</th>
            <th>Age</th>
            <th>Start Date</th>
            <th>Salary</th>
          </tr>
        </thead>
      </table>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'DataTablesPage',
  mounted () {
    $('#datatables').DataTable()
  }
})
</script>

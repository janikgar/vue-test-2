<template>
  <table class="table table-striped painTable">
    <tr>
      <th>Pain Level</th>
      <th>Date</th>
    </tr>
    <tr v-for="(painLevel, index) in painLevels" :key="index">
      <td>{{ painLevel.painLevel }}</td>
      <td>{{ painLevel.date }}</td>
    </tr>
  </table>
</template>

<script>
export default {
  name: 'PainTable',
  data () {
    return {
      painLevels: [
        {
          painLevel: '9',
          date: '2018-08-19 05:00'
        },
        {
          painLevel: '7',
          date: '2018-08-19 07:00'
        }
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
</style>

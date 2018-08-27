<template>
  <form>
    <div class="form-group">
      <label for="input-pain">Pain Level (0-10)</label>
      <input type="number" min=0 max=10 id="input-pain" class="form-control" />
      <label for="input-pain">Date</label>
      <input type="date" id="input-date" class="form-control" />
    </div>
  </form>
</template>

<script>
export default {
  name: 'input-info'  
}
</script>

<style>

</style>

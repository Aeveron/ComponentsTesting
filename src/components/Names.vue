<template>

<div class="components">
  <p>Test</p>
  <p>{{ msg }}</p>

</div>
</template>

<script>
export default {
  data: function() {
    return {
      msg: 'HEISANN!',
      name: 'Names'
    }
  }
}
</script>

<style scoped>
  p {
    color: blue;
  }
</style>
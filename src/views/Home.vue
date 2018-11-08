<template>
  <div class="components">
    <input type="button" value="Hei" id="btn1"></input>
  <names></names>
  </div>
</template>

<script>
import Names from '@/components/Names.vue';

export default {
  name: 'Names',
  components: {
    Names
  }
}
</script>

<style scoped>
#btn1{
  padding: 1%;
}
</style>


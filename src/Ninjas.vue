<template>
  <ul>
      <li v-bind="ninja in ninjas">{{ ninja }}</li>
  </ul>
</template>

<script>
export default {
  data() {
 return {
    ninjas: ['Yoshi','Mario','Ryu']
   }
  }
}
</script>

<style>

</style>
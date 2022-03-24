<script>
export default {
  data() {
    return {
      titleClass:'title'
    }
  }
}
</script>

<template>  
  <h1 v-bind:class="titleClass">Make me red</h1>        
</template>

<style>
  .title {
    color: red;
  }
</style>

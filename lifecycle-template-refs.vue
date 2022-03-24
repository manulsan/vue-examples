<script>
export default {
  mounted() {
    this.$refs.p1.textContent = 'mounted!'
    this.$refs.p2.textContent = 'mounted! 2'
  }
}
</script>

<template>
  <p ref="p1">hello</p>
  <p ref="p2">hello p2</p>
</template>

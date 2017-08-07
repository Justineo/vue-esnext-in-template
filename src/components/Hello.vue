<template>
<div :class="{ a: true, ...b }">Test</div>
</template>

<script>
export default {
  data () {
    return { b: true }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.a {
  color: blue;
}

.b {
  font-size: 30px;
}
</style>

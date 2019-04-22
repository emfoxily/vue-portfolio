<template>
  <div class="wrapper">
    <h1>This works!</h1>
  </div>
</template>

<script>
export default {
  name: 'Main',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1 {
    color: hotpink;
  }
</style>

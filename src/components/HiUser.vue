<template>
  <div class="helloMessage">
   <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: 'HiUser',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

</style>

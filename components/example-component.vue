<template>
  
</template>

<script>
export default {
    name:"exampel-component",
mounted () {
    this.$hello('mounted')
    // will console.log 'Hello mounted!'
  },
  asyncData ({ $hello }) {
    $hello('asyncData')
  }
}
</script>

<style>

</style>
<template>
  <div class="jumbotron">{{ msg }}</div>
</template>

<script>
export default {
  data() {
    return {
      msg: 'jumbotron'
    }
  }
}
</script>

<style>
.jumbotron {
  color: red;
}
</style>
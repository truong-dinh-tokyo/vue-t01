<template>
    <h1 class="red">{{msg + text}}</h1>
</template>

<script>
export default {
    props: ['msg'],
  data () {
    return {
      text: ' AAA!'
    }
  }
}
</script>

<style>
.red {
  color: #999;
}
</style>
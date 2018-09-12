<template>
  <div id="app">
    <layOut></layOut>
  </div>
</template>

<script>
import LayOut from './components/LayOut'

export default {
  components: {
    'layOut': LayOut
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
ul,ol,li{
  list-style: none;
}
a{
  text-decoration: none;
  color: #333;
}
</style>


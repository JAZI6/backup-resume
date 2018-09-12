<template>
  <div class="layout">
    <left></left>
    <right></right>
  </div>
</template>

<script>
import Left from './Left'
import Right from './Right'

export default {
  components: {
    'left': Left,
    'right': Right
  }
}
</script>

<style lang="scss">
.layout{
  font-family: "Avenir","Open Sans","Helvetica Neue",Helvetica,Arial,sans-serif;
  color: #333;
  font-size: 16px;
  width: 1100px;
  margin: 30px auto;
  padding: 0 30px;
  padding-bottom: 30px;
  background-color: #dfdfdf;
  border-radius: 20px;
  display: flex;
  justify-content: space-between;
}
</style>


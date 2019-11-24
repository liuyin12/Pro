<template>
  <div id="app">
    app
    <el-radio v-model="radio" label="1">备选项</el-radio>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      radio: '1'
    }
  }
}
</script>

<style lang="less">

</style>

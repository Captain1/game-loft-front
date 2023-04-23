<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div>
      <el-button @click="register">注册</el-button>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    register () {
      this.$notify({
        title: '注册动作',
        type: 'success',
        message: '注册触发!',
        duration: 5000
      })
    }
  }
}
</script>

<style>
#app {
  font-family: Helvetica, sans-serif;
  text-align: center;
}
</style>

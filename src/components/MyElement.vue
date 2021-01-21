<template>
  <el-button type="text" @click="open">点击这里打开ElenebtUI提供的[Message Box]</el-button>
</template>

<script>
export default {
  name: "MyElement",
  props: {
    msg: String
  },
  methods: {
    open() {
      this.$alert(this.msg, 'ElementUI MessageBox', {
        confirmButtonText: '确定',
        callback: action => {
          this.$message({
            type: 'info',
            message: `action: ${ action }`
          });
        }
      });
    }
  }
}
</script>

<style scoped>

</style>

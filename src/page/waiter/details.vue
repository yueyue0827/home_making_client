<template>
  <div class="datails">
    <el-button type="primary" size="mini" @click="backwaiter">返回</el-button>
  </div>
</template>
<script>
export default {
  methods: {
    backwaiter() {
      this.$router.go(-1)
    }
  }
}
</script>
<style scoped>
    .datails {
        padding: 1em 0.8em}
</style>


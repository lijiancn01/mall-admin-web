<template>
  <div class="app-container">
    <el-input
      type="textarea"
      autosize
      placeholder="请输入内容"
      v-model="textarea2">
    </el-input>
    <div style="margin: 20px 0;"></div>
    <el-input
      type="textarea"
      :rows="4"
      placeholder="请输入内容"
      v-model="textarea">
    </el-input>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        textarea: '',
        textarea2:''
      }
    }
  }
</script>

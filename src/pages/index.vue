<script>
export default {
  data() {
    return {
      name: 'page',
      input: '1',
    }
  },
  methods: {
    click() {
      console.log('1')
      this.name = '2'
    },
  },
}
</script>

<template>
  <div>
    <p>{{ name }}</p>
    <el-button type="primary" @click="click">按钮</el-button>
    <el-input v-model="input" placeholder="请输入内容"></el-input>
  </div>
</template>

<style></style>

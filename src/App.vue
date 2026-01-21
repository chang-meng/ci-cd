<template>
  <div>
    <h1>{{ message }}</h1>
    <p>欢迎使用 Vite + Vue3 项目</p>
    <p>这是一行简单的内容展示</p>
  </div>
</template>

<script>
import { ref } from 'vue'

export default {
  name: 'App',
  setup() {
    const message = ref('Hello Vite + Vue3!')

    return {
      message
    }
  }
}
</script>

<style>
h1 {
  color: #42b883;
  text-align: center;
}
</style>
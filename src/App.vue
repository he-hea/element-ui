<template>
  <customTable></customTable>
</template>

<script>
import { defineComponent } from 'vue'
import { ElButton } from 'element-plus'
import customTable from './components/customTable.vue'
export default {
  name: 'App',
  components: {
    ElButton,
    customTable
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

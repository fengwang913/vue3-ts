<template>
  <div class="about">
    <h1>This is an about page</h1>
    <el-button type="primary">I am elbutton</el-button>
  </div>
</template>


<script lang="ts">
import { ElButton } from 'element-plus'
export default {
    components: { ElButton },
  }


</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>

<template>
  <div class="block">
    <span class="demonstration">区分颜色</span>
    <el-rate
      v-model="value2"
      :colors="['#99A9BF', '#F7BA2A', '#FF9900']">
    </el-rate>
  </div>
</template>
<script>
  export default {
    data() {
      return {
        value2: null
      }
    }
  }
</script>
<style></style>

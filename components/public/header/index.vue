<template>
  <div class="m-header">
    <el-row>
      <topbar/>
    </el-row>
    <el-row>
      <searchbar/>
    </el-row>
  </div>
</template>

<script>
import topbar from './topbar.vue'
import searchbar from './searchbar.vue'
export default {
  components: {
    topbar,
    searchbar
  }
}
</script>

<style lang="scss">
@import '@/assets/css/public/header/index.scss';
</style>

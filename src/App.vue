<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import { defineComponent } from 'vue'
  import { ElConfigProvider } from 'element-plus'

  import zhCn from 'element-plus/lib/locale/lang/zh-cn'

  export default defineComponent({
    components: {
      ElConfigProvider,
    },
    setup() {
      return {
        locale: zhCn,
      }
    },
  })

</script>

<template>
  <router-view></router-view>
</template>

<style scoped>
</style>

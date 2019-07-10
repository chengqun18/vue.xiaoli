<template>
  <div>
    <h3>MemberContainer</h3>
    <mt-button type="primary">primary</mt-button>
    <button type="button" class="mui-btn mui-btn-warning">黄色</button>
  </div>
</template>

<script>
  import { Toast } from 'mint-ui';
  
  export default {
    created() {
      Toast({
        // message: '小姐姐真好看',
        duration: 3000
      });
    }
  }
</script>

<style lang="scss" scoped>

</style>

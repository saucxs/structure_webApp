<template>
  <header class="header">
    <h2 class="header-logo">structure_webApp</h2>
  </header>
</template>

<script>
  import { mapState } from 'vuex';
export default {
  name: 'tababr',
  data () {
    return {

    }
  }
}
</script>

<style scoped lang="scss">
  .header {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    width: 100%;
    height: 40px;
    overflow: hidden;
    color: #fff;
    background-color: #5579ee;
    box-sizing: border-box;
    z-index: 99;

    h2.header-logo {
      position: absolute;
      top: 12px;
      left: 15px;
      color: #fff;
      line-height: 20px;
    }
  }
</style>

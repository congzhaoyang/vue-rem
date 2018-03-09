<template>
  <div class="wrap">
    <header>
      <div class="div1">
        天天玩耍
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: 'Demo',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss" scoped>
.wrap {
  header {
    .div1 {
      width: 100%;
      height: 150px;
      background-color: aquamarine;
      border-bottom: 1px solid blue;
      font-size: 16px;
    }
  }
}
</style>


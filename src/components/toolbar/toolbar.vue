<style lang="stylus">
  @import "global.styl"

  .toolbar
    display flex
    flex-wrap nowrap
    justify-content space-between
    align-items stretch
    height $toolbar-height
    line-height $toolbar-height
    background-color $toolbar-background-color
    color $toolbar-text-color
    font-size 20px
    font-weight 500
    padding 0 24px
    user-select none
</style>

<template>
  <div class="toolbar">
    <slot></slot>
  </div>
</template>

<script>
  export default {
  };
</script>

<template>
  <div class="wrapper">
    <div class="line"></div>
    <div class="word">{{word}}</div>
    <div class="line"></div>
  </div>
</template>

<script type="text/ecmascript-6">
  export default {
    props: {
      word: String
    }
  };
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .wrapper
    display: flex
    width: 80%
    margin: 28px auto 24px auto
    .line
      flex: 1
      position: relative
      top: -6px
      border-bottom: 1px solid rgba(255, 255, 255, 0.2)
    .word
      padding: 0 12px
      font-weight: 700
      font-size: 14px
</style>

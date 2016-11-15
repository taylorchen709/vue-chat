<template>
  <section class="foot">
      <mt-field placeholder="请输入消息"></mt-field>
  </section>
</template>

<script>
export default {
  name: 'foot',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .foot {
    width: 100%;
    height: 50px;
    position: absolute;
    bottom: 0px;
    left: 0px;
    background-color: #F8F8F8;
  }
</style>
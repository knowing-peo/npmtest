<template>
  <div class="container">
    <span>Hello NPM demo!</span>
    <span class="txt">{{ data.name }}</span>
  </div>
</template>
<script>
export default {
  name:'MSG',
  props:{
    data:{
      type: Object,
      default: ()=>{}
    }
  },
  data(){
    return {}
  },

}
</script>
<style lang="scss" scoped>
  @import url('./css/common.scss');
</style>


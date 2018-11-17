<template lang="html">
  <div class="sample">
    <div>
      <slot/>
    </div>
    <div class="blue">
      <slot name="named"/>
    </div>
  </div>
</template>
​
<script>
export default {
  props: {
    indexTitle: {
      type: String,
      default: 'Defalut Title'
    }
  }
}
</script>
​
<style lang="scss" scoped>
</style>

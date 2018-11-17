<template lang="html">
  <section>
    <sample-component>
      Hello Slot!
      <div slot="named">
        named slot
      </div>
    </sample-component>
    <nuxt-link to="/about">ABOUT</nuxt-link>
  </section>
</template>

<script>
import SampleComponent from '~/components/SampleComponent.vue'

export default {
  components: {
    SampleComponent
  },
  data() {
    return {
      indexTitle: 'Nuxt.js Data'
    }
  }
}
</script>

<style lang="scss" scoped>
.hide {
  display: none;
  &.seven {
    display: block;
  }
}
</style>

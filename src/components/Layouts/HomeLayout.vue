<template lang="">
    <div>
        <header-vue />
            <slot> </slot>
        <footer-vue />
    </div>
</template>
<script>
import FooterVue from '../Footer.vue'
import HeaderVue from '../Header.vue'
export default {
  components: {
      HeaderVue,
      FooterVue
  }  
}
</script>
<style lang="scss">
    
</style>
<template lang="">
    <div class="layout">
        <header-vue />
            <div class="content">
                <slot> </slot>
            </div>
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
<style lang="scss" scoped>
    .layout{
        display: flex;
        flex-direction: column;
        min-height: 100vh;
    }
    .content{
        flex: 1;
    }
</style>
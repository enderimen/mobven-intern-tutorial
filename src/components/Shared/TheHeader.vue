<template>
  <header class="header">
      <container>
          logo
          btn
          class="btn-icon"
      </container>
  </header>
</template>
<script>
import Container from '../common/Container.vue'

export default {
    components: {
        Container
    }
}
</script>

<style lang="scss" scoped>
.header {
    height: 80px;
    width: 100%;
    background: #fff;
    box-shadow: 1px 1px 10px rgba(0,0,0, .5);
    margin-bottom: 50px;
}
</style>
<template>
  <button class="btn" :class="[color, size]">
      <slot />
  </button>
</template>

<script>
export default {
  props: {
    color: {
      type: String
    },
    size: {
      type: String
    }
  }
}
</script>

<style lang="scss" scoped>
.btn {
  border: none;
  height: 30px;
  width: 120px;
  background-color: red;
  color: #fff;
  border-radius: 20px;

  // colors
  &.green {
    background-color: green;
  }
  &.orange {
    background-color: orange;
  }

  // sizes
  &.medium {
    width: 200px;
  }
  &.large {
    width: 250px;
  }
}
</style>
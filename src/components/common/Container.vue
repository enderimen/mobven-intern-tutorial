<template>
  <div class="container">
    <slot />
  </div>
</template>

<style lang="scss" scoped>
.container {
  margin-left: auto;
  margin-right: auto;
  padding-left: 15px;
  padding-right: 15px;
  border: 1px solid red;
}

@media only screen and (max-width: 600px) {
    // .container {
    //     background-color: red;
    // }
}

@media only screen and (min-width: 600px) {
    // .container {
    //     background-color: green;
    // }
}

@media only screen and (min-width: 768px) {
    // .container {

    // }
}

@media only screen and (min-width: 992px) {
    .container {
        width: 920px;
    }
}

@media only screen and (min-width: 1200px) {
    .container {
        width: 1200px;
    }
}
</style>
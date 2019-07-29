<template>
  <div class="main">
      <div class="container">
        <slot></slot>
      </div>
  </div>
</template>

<script>
export default {
  name: "Main"
};
</script>

<style lang="scss" scoped>
.main {
  margin-left: 18vw;
  overflow-y: scroll auto;
  width: calc(100vw - 18vw);
  height: 100%;

  .container {
    padding: 0;
  }
}
</style>


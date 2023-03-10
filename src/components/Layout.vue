<template>
  <div class="nav-wrapper">
    <div class="content">
      <slot></slot>
    </div>
    <Nav/>
  </div>
</template>

<script>
export default {
  name: "Layout"
}
</script>

<style lang="scss" scoped>
.nav-wrapper{
  border: 1px solid red;
  height: 100vh;
  display: flex;
  flex-direction: column;
}
.content{
  overflow: auto;
  flex-grow: 1;
}
</style>
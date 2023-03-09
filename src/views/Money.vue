<template>
  <div class="nav-wrapper">
    <div class="content">
      <p>money.vue</p>
    </div>
    <Nav/>
  </div>
</template>

<script>
export default {
  name: "Money",
}
</script>

<style lang="scss" scoped>
.nav-wrapper{
  border: 1px solid red;
  background-color: #42b983;
  height: 100vh;
  display: flex;
  flex-direction: column;
}
.content{
  background-color: coral;
  overflow: auto;
  flex-grow: 1;
}
</style>
<template>
  <div>
    <router-link to="/money">
      <Icon name="money"/>
      记账
    </router-link>|
    <router-link to="/labels">
      <Icon name="label"/>
      标签
    </router-link>|
    <router-link to="/statistics">
      <Icon name="statistics"/>
      统计
    </router-link>
  </div>
</template>

<script lang="ts">
import x from '@/assets/icons/money.svg'
import y from '@/assets/icons/label.svg'
import z from '@/assets/icons/statistics.svg'
console.log(x)
console.log(y)
console.log(z)
export default {
  name: "Nav"
}
</script>
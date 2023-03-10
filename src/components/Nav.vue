<template>
  <div>
    <router-link to="/money">
      <svg>
        <use xlink:href="#money"/>
      </svg>
      记账
    </router-link>|
    <router-link to="/labels">
      <svg>
        <use xlink:href="#label"/>
      </svg>
      标签
    </router-link>|
    <router-link to="/statistics">
      <svg>
        <use xlink:href="#statistics"/>
      </svg>统计
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
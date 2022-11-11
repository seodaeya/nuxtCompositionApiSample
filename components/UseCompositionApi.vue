<template>
  <div>
    <h1>숫자</h1>
    <input type="text" :value="num" />
    <h1>글자</h1>
    <input type="text" :value="txt" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'IndexPage',

  setup() {
    const num: number = 1
    const txt: string = 'text'

    return { num, txt }
  },
})
</script>

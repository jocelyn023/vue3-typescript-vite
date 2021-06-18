<template>
  <div>{{ state.msg }} 时光正好，未来可期，加油 ！</div>
</template>

<script lang="ts">
import { defineComponent, reactive } from 'vue'
export default defineComponent({
  name: 'index',
  setup () {
    const state = reactive({
      msg: 'sdasdasd'
    });
    return { state };
  }
})
</script>
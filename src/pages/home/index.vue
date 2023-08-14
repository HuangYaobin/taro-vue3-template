<script setup lang="ts">
import { ref } from 'vue'
const count = ref(1)
function increase() {
  count.value++
}
</script>

<template>
  <view>
    <view>home</view>

    <view>count: {{ count }}</view>

    <button @tap="increase">增加</button>
  </view>
</template>

<template>
  <view class="container">
    <view>
      <text class="text-3xl text-neutral-600 m-6 text-center">{{
        greeting
      }}</text>
    </view>
  </view>
</template>

<script setup>
import { ref } from 'vue';

const greeting = ref('hello');
</script>

<script setup lang="ts">
// TODO: make count reactive, so that it updates when it is changed (reactivity)
// TODO: log the latest value of count when it is updated (watch)
const count = 0

// TODO: add another counter that tracks the total number of clicks across all buttons (computed)
</script>

<template>
  <div>
    <!-- TODO: make title customizable (props) -->
    <p>I like to count</p>

    <!-- TODO: make this update when the count is updated (reactivity)-->
    <span class="counter-text">Current count: {{ count }}</span>

    <!-- TODO: add two buttons, one that decrements and another that increments the count when clicked -->
    <!-- TODO: break out this button into a component that can customize the text and event when clicked (emit, props/slots) -->
  </div>
</template>

<style scoped>
.counter-text {
  margin-right: 12px;
}
</style>

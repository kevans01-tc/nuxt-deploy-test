<script setup>
  const route = useRoute();
</script>

<template>
  <div>products {{ route.params.product_name }}</div>
</template>

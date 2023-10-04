<script setup>
  const route = useRoute();
</script>

<template>
  <div>categories {{ route.params.category_name }}</div>
</template>

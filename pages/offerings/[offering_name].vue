<script setup>
  const route = useRoute();
</script>

<template>
  <div>offerings {{ route.params.offering_name }}</div>
</template>

<script setup lang="ts">
const route = useRoute();
navigateTo(`${route.path.replace("/books", "/libros")}`, { replace: true });
</script>

<template>
  <div class="flex items-center justify-center">
    Re-redireccionando...
  </div>
</template>

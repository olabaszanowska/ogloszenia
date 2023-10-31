<script setup lang="ts">
const route = useRoute();
console.log(route.params.slug)
</script>

<template>
{{ $route.params.slug }}
<!-- powyzej jest slowo slug poniewaz wystepuje tez w nazwie tego pliku -->
</template>

<style scoped>

</style>
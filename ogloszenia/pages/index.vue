<script setup lang="ts">
const route = useRoute()
</script>

<template>
    <div><img src="logo.png" alt="logo"></div>
    <div>
        <h2>Panel ogłoszeniowy</h2>
        <p>Zaloguj się, aby uzyskać dostęp do panelu ogłoszeniowego Uniwersytetu WSB Merito w Gdańsku i Gdyni.</p>
        <p>Current route: {{ route.path }}</p>
    </div>
</template>
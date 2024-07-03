<template>
  <div>
    <h1>Rota protegida</h1>
    <UButton @click="logout">Sair</UButton>
  </div>
</template>

<script setup>
const { logout } = useFirebaseAuth();
</script>

<style>
</style>
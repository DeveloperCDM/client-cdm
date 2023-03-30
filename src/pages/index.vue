<template>
  <VCard radius="large">
    <h3 class="title is-5 mb-2">Instruções</h3>
    <ul>
      <li>Passo 1: Crie a tabela em HTML</li>
      <li>Passo 2: Crie as funções CRUD usando a API do laravel</li>
    </ul>
  </VCard>
  <VCard radius="large" style="text-align: center;">
   TABELA AQUI
  </VCard>
</template>

<script setup lang="ts">
import { useHead } from '@vueuse/head'

useHead({
  title: 'Clube do Malte',
})

onMounted(() => {
  console.log('Boa sorte!')
})
</script>


<style lang="scss">
@import '/@src/scss/abstracts/all';
@import '/@src/scss/_demo/landing';
</style>

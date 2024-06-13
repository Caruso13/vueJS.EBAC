<script setup>
const nome = "Ângelo Caruso"
const meuObj = {
  nome: "Ângelo",
  filmeFavorito: "Rocky"
}

function dizOla(nome) {
  return `${nome} diz oi`
}


</script>
<template>
  <h1>{{ dizOla() }}</h1>
</template>

<style scoped>

</style>
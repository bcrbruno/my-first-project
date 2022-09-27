<template>
  <div>
    <h2>Olá amigos!</h2>
    <p>Meu nome é {{ nome }}, trabalho na {{ empresa }} como {{ profissao }}</p>
    <p>Estou estudando algumas funcionalidades. <button v-on:click="reverseMessage">Clique neste botão</button></p>
  </div>
</template>

<script>
  export default {
      name: 'PrimeiroComponente',
      data() {
          return {
              nome: "Bruno Rodrigues",
              profissao: "Analista de suporte",
              empresa: "Vonix Tecnologia"
          }
      }
    }
</script>

<style>

</style>
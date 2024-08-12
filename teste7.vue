<template>
    <div class="row">
      <div class="col box1"><card-info></card-info> <card-demanda></card-demanda></div>
      <div class="col box1"><card-read></card-read> <br><br><card-read-2></card-read-2></div>
    </div>
    <div class="row">
    </div>
  </template>
 
 <style>
 .row {
  display: flex; /* Utiliza flexbox para layout em linha */
  gap: 5px; /* Espaçamento entre colunas dentro de uma linha */
  margin-bottom: 10px; /* Espaçamento entre linhas */
}

.col {
  flex: 1; /* Cada coluna ocupa a mesma quantidade de espaço */
  min-width: 0; /* Evita que as colunas ultrapassem o tamanho da linha */
}

.box1, .box2 {
  padding: 10px; /* Adiciona algum preenchimento interno */
  box-sizing: border-box; /* Inclui padding e border no tamanho total do elemento */
}

.box1 {
  background-color: rgb(102, 255, 0); /* Altere a cor de fundo */
}

.box2 {
  background-color: aqua; /* Altere a cor de fundo */
}
</style>
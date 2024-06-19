<script setup>

</script>


<template>
  <div class="container">
    <header class="p-5 mb-4 mt-4 bg-light rounded-3">
      <h1>Minhas tarefas</h1>
      <p>
        Você possui 7 terefas pendentes
      </p>
    </header>
  </div>
  <form>
    <div class="row">
      <div class="col">
        <input type="text" placeholder="Digite aqui a descrição da tarefa" class="form-control"> 
      </div>
      <div class="col-md-1"></div>
      <button type="submit" class="btn btn-primary">cadastrar</button> 
    </div>
    <div class="col-md-2">
      <select class="form-control">
        <option value="todas">Todas tarefas</option>
        <option value="Pendentes">Pendentes</option>
        <option value="Finalizadas">Finalizadas</option>
      </select>
    </div>
  </form>
</template>

<style scoped>
</style>
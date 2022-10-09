<template>
  <header>
    <div class="menu-esquerdo">
      <span> <RouterLink to="/">Home</RouterLink> </span>
      <span>|</span>
      <span><RouterLink to="/gerenciamento">Livros</RouterLink></span>
      <span>|</span>
      <span><RouterLink to="/categorias">Categorias</RouterLink></span>
      <span>|</span>
      <span><RouterLink to="/autores">Autor</RouterLink></span>
      <span>|</span>
      <span><RouterLink to="/editoras">Editora</RouterLink></span>
    </div>
    <div class="menu-direito">
      <span><RouterLink to="/tomeumcookie">Cookie</RouterLink></span>
    </div>
  </header>
</template>
<style>
header {
  height: 10%;
  color: black;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  padding-left: 20px;
  justify-content: space-between;
}
header span {
  padding: 0 20px;
  text-decoration: none;
}
</style>

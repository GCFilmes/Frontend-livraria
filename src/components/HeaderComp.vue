<template>
  <header>
    <div class="navbar">
      <RouterLink to="/autor" class="navAutor">Autor</RouterLink>
      <RouterLink to="/editora" class="navEditora">Editora</RouterLink>
      <RouterLink to="/categoria" class="navCategoria">Categoria</RouterLink>
      <RouterLink to="/livros" class="navLivros">Livros</RouterLink>
    </div>
  </header>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Secular+One&display=swap');

header {
  position: absolute;
  width: 100%;
  height: 130px;
  left: 0;
  top: 0;

  background-image: linear-gradient(90deg,
      #222121 0,
      #49494b 35%,
      #747474 100%);
}

.adm {
  position: absolute;
  left: 40px;
  top: 35px;
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 900;
  font-size: 35px;
  line-height: 59px;
  text-align: left;
  color: #ffffff;
}

.navbar {
  margin: 2% 0 0 0%;
  font-size: 20px;
  font-family: 'Secular One', sans-serif;
}

.navAutor {
  color: #ffffff;
  text-decoration: none;
  margin: 0 auto;
}

.navEditora {
  color: #ffffff;
  text-decoration: none;
  margin: 0 auto;
}

.navCategoria {
  color: #ffffff;
  text-decoration: none;
  margin: 0 auto;
}

.navLivros {
  color: #ffffff;
  text-decoration: none;
  margin: 0 auto;
}
</style>

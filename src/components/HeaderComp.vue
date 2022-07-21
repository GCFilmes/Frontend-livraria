<template>
  <header>
    <main>
      <div class="navbar">
        <div class="painel"><RouterLink to="/autor" class="navpainel"><span>Painel de Administração</span></RouterLink></div>
          <RouterLink to="/autor" class="navAutor">Autor</RouterLink>
          <RouterLink to="/editora" class="navEditora">Editora</RouterLink>
          <RouterLink to="/categoria" class="navCategoria">Categoria</RouterLink>
          <RouterLink to="/livros" class="navLivros">Livros</RouterLink>
      </div>
    </main>
  </header>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Secular+One&display=swap');

main {
  background-color: #6c3a3a;
  position: absolute;
  width: 265px;
  height: 100vh;
  left: 0px;
  top: 0px;
}
.painel {
  background: #d9d9d9;
  border-radius: 32px;
  position: absolute;
  width: 1250px;
  height: 131px;
  left: 167px;
  top: 53px;
}
.painel span {
  position: absolute;
  width: 780px;
  height: 59px;
  left: 40px;
  top: 35px;
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 900;
  font-size: 35px;
  line-height: 59px;
  text-align: left;
  color: #6c3a3a;
  display: block;
}
.imglivro {
  position: absolute;
  right: 24px;
  top: 15px;
  width: 150px;
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

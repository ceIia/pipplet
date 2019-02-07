<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="https://bulma.io">
      <img src="../assets/logo.png">
    </a>
  </div>

  <div class="navbar-end">
    <a class="navbar-item active">Accueil</a>
    <a class="navbar-item">Entreprises</a>
    <a class="navbar-item">Organismes de formation</a>
    <a class="navbar-item">Pourquoi choisir Pipplet ?</a>
    <a class="navbar-item">Tarifs</a>
    <a class="navbar-item">Contact</a>
    <a class="navbar-item">Blog</a>
    <a class="navbar-item access">
      <p class="access">Accéder à Pipplet</p>
    </a>
    <a class="navbar-item lang"><img src="../assets/fr.png" alt=""></a>
  </div>
</nav>
</template>


<style lang="scss" scoped>
nav {
  margin: 0 2em;
}

a.access {
  color: white;
  margin-left: 10px;
  transition: .2s;
  &:hover {
    & p.access {
      background-color: rgb(32, 147, 255);
      color: #fff;
    }
  }
}

p.access {
  background-color: #0084FF;
  border-radius: 50px;
  padding: 10px 30px;
  transition: .2s;
}

.active::after {
  content: '';
  justify-content:center;
  position: absolute;
  display: inline-block;
  height: 1em;
  width: 70%;
  left: 15%;
  border-bottom: 1px solid;
  margin-top: .3rem;
}

.lang {
  margin: 0 35px;
}

a {
  font-size: 12px;
}
</style>


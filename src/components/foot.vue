<template>

<footer class="footer">
  <div class="content">
    <div class="columns">
      <div class="column is-one-third is-centered">
        <img width="200" class="" src="../assets/logo-wh@2x.png" alt="">
        <p class="is-centered nyaaa">
            10 rue de Penthièvre<br>
            75008 Paris<br>
            RCS Paris 813 493 673 673 00012
        </p>
      </div>
      <div class="column is-one-third is-centered">
        <ul class="foot-list mid">
          <li>Blog</li>
          <li>À propos de nous</li>
          <li>Devenez évaluateur</li>
          <li>Nos partenaires</li>
          <li>Glossaire</li>
        </ul>
      </div>
      <div class="column is-one-third is-centered">
        <ul class="foot-list last">
          <li>
          <p class="access blue">Accéder à Pipplet</p></li>
          <li>Blog</li>
          <li>À propos de nous</li>
          <li>Devenez évaluateur</li>
          <li>Nos partenaires</li>
          <li>Glossaire</li>
        </ul>
      </div>
    </div>
    <div class="is-centered">
      <p>&copy; Pipplet 2018 — Tous droits réservés &bull; CGPS &bull; Confidentialité</p><br>
      <img src="https://www.la-rache.com/img/logo.png" alt="ISO-1664"><br>
      <p class="is-size-7 warn">
        Réalisé dans le cadre d’un projet étudiant collaboratif entre les écoles SUP’Internet, ISEG, E-Artsup, ainsi que IONIS 361 et Pipplet.<br>
        Ce document est destiné a des fins éducatives, et ne pourra pas être utilisé a des fins commerciales par aucun des partis.<br>
        Ce document est confidentiel, et n’est pas autorisé à la redistribution ni à la consultation par des tiers sauf accord préalable.
      </p>
    </div>
  </div>
</footer>
  
</template>


<style lang="scss" scoped>
p {
  color: #fff;
  &:not(.nyaaa) {
    display: inline-block;
  }
}

.warn {
  color: rgb(94, 172, 245);
}

.access {
  background-color: #fff;
  color: #0084FF;
  width: fit-content;
  text-align: center;
  padding: 10px 20px;
  margin-bottom: 10px;
  border-radius: 50px;
}

ul {
  margin-left: 0 !important;
  &.mid {
    margin-top: 4rem !important;
  }
  &.last {
    margin-top: 1rem !important;
  }
}

.foot-list {
  list-style-type: none;
  color: #fff;
}
</style>

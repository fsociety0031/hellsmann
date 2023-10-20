<script setup>
import CommunityIcon from './icons/IconCommunity.vue'
</script>
<template>
  <nav class="navbar navbar-expand-lg bg-y">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <router-link to="/">HOME</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/">COMO<br>PARTICIPAR</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/">PRÊMIOS</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/">PRODUTOS<br>PARTICIPANTES</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/">RECEITAS</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/">PÍLULAS NBA</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/">GANHADORES</router-link>
          </li>
          <li class="nav-item btn_">
            <a href="#!">OLÁ, ANA <CommunityIcon/></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<style scoped>
li > * {
  font-family: brandon-grotesque, sans-serif;
  font-weight: 700;
  color: #084972;
  text-decoration: none;
  text-align: center;
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  align-items: center;
  justify-content: center;
  font-size: 17px;
  line-height: 18px;
  height: 100%;
}
.bg-y {
  background: #FACC1F;
}
li.nav-item {
    padding-left: 15px;
    padding-right: 15px;
    height: 100%;
}
.navbar {
  padding: 0
}

.btn_ {
  background: #074A75;
}

.btn_ a {
  color: #FACC1F;
  display: flex;
  flex-direction: row;
}

.container-fluid {
  height: 100%;
}

div#navbarNav {
  height: 100%;
}
.navbar-nav {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
}

nav {
  height: 64px;
}
</style>
<template>
  <section class="container-fluid">
    <h2>COMPRE, JUNTE E TROQUE</h2>
    <div class="selector">
      <a href="#!" :class="{ selected: selectedTag === 'PRATOS' }" @click="selectTag('PRATOS')">PRATOS</a>
      <a href="#!" :class="{ selected: selectedTag === 'BOWLS' }" @click="selectTag('BOWLS')">BOWLS</a>
      <a href="#!" :class="{ selected: selectedTag === 'TABUA' }" @click="selectTag('TABUA')">TÁBUA</a>
    </div>
    <div class="plates space" v-show="selectedTag === 'PRATOS'">
      <picture>
        <source media="(max-width: 991px)" srcset="../assets/imgs/galeria/galeria-pratos-mob.png">
        <source media="(min-width: 992px)" srcset="../assets/imgs/galeria/galeria-pratos.png">
        <img src="../assets/imgs/galeria/premios-pratos-mob.png" alt="">
      </picture>
    </div>
    <div class="bowls space" v-show="selectedTag === 'BOWLS'">
      <picture>
        <source media="(max-width: 991px)" srcset="../assets/imgs/galeria/galeria-bowls-mob.png">
        <source media="(min-width: 992px)" srcset="../assets/imgs/galeria/galeria-bowls.png">
        <img src="../assets/imgs/galeria/premios-bowls-mob.png" alt="">
      </picture>
    </div>
    <div class="tabua space" v-show="selectedTag === 'TABUA'">
      <picture>
        <source media="(max-width: 991px)" srcset="../assets/imgs/galeria/galeria-tabua-mob.png">
        <source media="(min-width: 992px)" srcset="../assets/imgs/galeria/galeria-tabua.png">
        <img src="../assets/imgs/galeria/premios-tabua-mob.png" alt="">
      </picture>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      selectedTag: 'PRATOS',
    };
  },
  methods: {
    selectTag(tag) {
      this.selectedTag = tag;
    },
  },
};
</script>

<style scoped>
.container-fluid {
  display: flex;
  flex-direction: column;
  justify-content: center;
  background: #122641;
  padding: 50px 40px 10px 40px;
  border-radius: 67px;
  margin-top: -22px;
  border: 17px solid #122641;
  box-sizing: border-box;
  box-shadow: 0px 0px 0px 5px #084C73 inset;
  position: relative;
  z-index: 2;
  align-items: center;
}

.space {
  margin-top: 40px;
  margin-bottom: 40px;
}

h2 {
  color: #F5CB21;
  font-family: 'brandon-grotesque';
  font-size: 32px;
  margin-bottom: 20px;
}

.selector a {
  font-family: 'brandon-grotesque';
  text-decoration: none;
  color: #fff;
  padding: 0px 25px 0px 25px;
  border-radius: 20px;
  text-align: center;
  display: flex;
  flex-direction: row;
  align-items: center;
}

.selected {
  background: #F5CB21;
  color: #074A76!important;
}
.selector {
  padding: 4px;
  width: 400px;
  display: flex;
  justify-content: space-between;
  background: #0B4877;
  border-radius: 50px;
  height: 36px;
}
@media (max-width: 991px) {
  .selector {
    width: auto;
  }
  img {
    width: 100%;
  }
}
</style>
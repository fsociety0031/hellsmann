<template>
  <section class="container-fluid">
    <h1>PRODUTOS PARTICIPANTES</h1>
    <picture>
      <source media="(max-width: 991px)" srcset="../assets/imgs/produtos/produtos-mob.png">
      <source media="(min-width: 992px)" srcset="../assets/imgs/produtos/produtos-prod.png">
      <img src="../assets/imgs/produtos/produtos-mob.png" alt="">
    </picture>
  </section>
</template>
<style scoped>
h1 {
  font-family: 'trend_sansfive';
  color: #FFF;
  font-size: 55px;
  border-bottom: 3px solid #FFF;
}

@media (min-width: 991px) {
  img {
    zoom: 140%;
    position: relative;
    bottom: -18px;
  }
}
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
@media (max-width: 991px) {
  h1 {
    font-size: 30px;
    text-align: center;
  }
  img {
    width: 100%;
  }
}
</style>
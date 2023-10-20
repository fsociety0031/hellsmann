<template>
  <section class="container-fluid">
    <picture>
      <source media="(max-width: 991px)" srcset="../assets/imgs/premios/premios-mob.png">
      <source media="(min-width: 992px)" srcset="../assets/imgs/premios/premios.png">
      <img src="../assets/imgs/premios/premios-mob.png" alt="">
    </picture>
  </section>
</template>
<style scoped>
.container-fluid {
  display: flex;
  flex-direction: row;
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
}
@media (max-width: 992px) {
  img {
    width: 100%;
  }
}
</style>
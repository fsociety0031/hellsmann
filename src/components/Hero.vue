<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-4">
        <button class="">PARTICIPE</button>
        <picture>
          <source media="(max-width: 991px)" srcset="../assets/imgs/home/logo-promo-mob.png">
          <source media="(min-width: 992px)" srcset="../assets/imgs/home/logo-promo.png">
          <img src="../assets/imgs/home/logo-promo-mob.png" alt="" class="colecionaveis">
        </picture>
      </div>
      <div class="col basket">
        <img class="unilever" src="../assets/imgs/home/logo-unilever.png" alt="">
        <button>PARTICIPE</button>
        <img src="../assets/imgs/home/produtos-home.png" alt="">
      </div>
    </div>
  </div>
</template>
<style scoped>
.container-fluid {
  height: 82vh;
}
.row {
  height: -webkit-fill-available;
  align-items: center;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
}
.basket {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  height: -webkit-fill-available;
  align-items: center;
}
.basket img{
  width: 100%;
  position: relative;
  top: 20px;
  left: -20px;
  max-width: 900px;
}

button {
  padding: 15px;
  width: 300px;
  border: 0px;
  border-radius: 70px;
  font-family: 'brandon-grotesque';
  font-size: 40px;
  color: #074B72;
  background: #FACC1F;
  box-shadow: 3px 4px 13px black;
  margin-bottom: 14px;
}

.unilever {
  width: fit-content!important;
  align-self: end;
  left: -100px!important;
  top: 18px;
  position: relative;
}

.colecionaveis {
  width: 144%;
}

@media (max-width: 991px) {
  .colecionaveis {
    width: 100%;
    position: relative;
    top: 21px;
  }
  .row {
    display: flex;
    flex-direction: column-reverse;
  }
  picture img {
    width: -webkit-fill-available;
  }
  .col-4 {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    height: -webkit-fill-available;
    justify-content: space-around;
  }
  .basket {
    display: none;
  }
  img {
    width: 100%;
  }
}
</style>
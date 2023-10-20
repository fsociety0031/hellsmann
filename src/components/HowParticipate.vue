<template>
  <section class="container-fluid">
    <h2>COMO PARTICIPAR</h2>
    <div class="passos-wrapper">
      <div class="passos">
        <img src="../assets/imgs/como-participar/passo-1.png" alt="">
        <img src="../assets/imgs/como-participar/passo-2.png" alt="">
        <img src="../assets/imgs/como-participar/passo-3.png" alt="">
        <img src="../assets/imgs/como-participar/passo-4.png" alt="">
      </div>
    </div>
    <div class="passos-wrapper">
      <div class="passos">
        <img src="../assets/imgs/como-participar/extra-1.png" alt="">
        <img src="../assets/imgs/como-participar/extra-2.png" alt="">
        <img src="../assets/imgs/como-participar/extra-3.png" alt="">
      </div>
    </div>
    <div class="passos-wrapper center">
      <div class="passos center">
        <img src="../assets/imgs/como-participar/extra-4.png" alt="">
        <button>PARTICIPE</button>
      </div>
    </div>
  </section>
</template>
<style scoped>
h2 {
  font-family: 'trend_sansfive';
  font-size: 40px;
  border-bottom: 2px solid;
  color: #FFF;
}

.passos-wrapper.center {
  margin-top: 0px;
}

.passos-wrapper {
  max-width: 1010px;
  width: inherit;
  margin-top: 30px;
}

.passos {
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: space-between;
}
.passos.center{
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}

button {
  padding: 15px;
  width: 270px;
  border: 0px;
  border-radius: 70px;
  font-family: 'brandon-grotesque';
  font-size: 40px;
  color: #074B72;
  background: #FACC1F;
  box-shadow: 3px 4px 13px black;
  margin-top: 16px;
}

.passos img {
  position: relative;
  display: block;
}
.container-fluid {
  z-index: 1;
  position: relative;
  background: #074A75;
  height: 96vh;
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  justify-content: flex-start;
  padding-top: 120px;
  padding-bottom: 53px;
  margin-top: -54px;
  align-items: center;
}
@media (max-width: 991px) {
  .passos-wrapper {
    display: flex;
    flex-direction: row;
    max-width: 100%;
    overflow: scroll;
  }
  .passos {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: flex-start;
  }
  .passos-wrapper.center {
    height: 100%;
  }
  .passos.center {
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
    overflow: hidden;
  }
}
</style>
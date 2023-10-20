<template>
  <section class="container-fluid">
    <h1>COMPRE AGORA E PARTICIPE</h1>
    <div class="flex">
      <div class="card bg-none">
        <img src="../assets/imgs/compre-agora/pda.png" alt="">
        <a href="#!">GPA</a>
      </div>
      <div class="card bg-none">
        <img src="../assets/imgs/compre-agora/carrefour.png" alt="">
        <a href="#!">CARREFOUR</a>
      </div>
    </div>
  </section>
</template>
<style scoped>
h1 {
  font-family: 'trend_sansfive';
  color: #FFF;
  font-size: 35px;
  border-bottom: 3px solid #FFF;
}

@media (min-width: 991px) {
  img {
    margin-top: 40px;
  }
  .flex {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    align-items: center;
    width: 360px;
    justify-content: space-around;
  }
}

a {
  padding-top: 10px;
  padding-left: 20px;
  padding-right: 20px;
  padding-bottom: 10px;
  text-align: center;
  background-color: #FACC1F;
  border-radius: 40px;
  text-decoration: none;
  font-family: brandon-grotesque;
  color: #124678;
  margin-top: 30px;
  box-shadow: 3px 4px 13px black;
}

.bg-none {
  background-color: transparent;
  border: 0px;
}
.container-fluid {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 50px 40px 10px 40px;
  border-radius: 67px;
  padding-bottom: 50px;
  box-sizing: border-box;
  /* box-shadow: 0px 0px 0px 5px #084C73 inset; */
  position: relative;
  z-index: 2;
  align-items: center;
}
@media (max-width: 991px) {
  h1 {
    text-align: center;
    margin-bottom: 50px;
  }
  a {
    margin-top: 20px;
    margin-bottom: 20px;
  }
}
</style>
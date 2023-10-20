<template>
  <div class="container-fluid">
    <div class="laco">
      <img src="../assets/imgs/footer/laco.png" alt="">
      <hr/>
    </div>
    <div class="container">
      <div class="regulamento">
        <a href="#!">DÚVIDAS</a>
        <a href="#!">REGULAMENTO</a>
      </div>
      <div class="redes">
        <a href="#!">
          <img src="../assets/imgs/footer/redes-twitter.png" alt="">
        </a>
        <a href="#!">
          <img src="../assets/imgs/footer/redes-facebook.png" alt="">
        </a>
        <a href="#!">
          <img src="../assets/imgs/footer/redes-instagram.png" alt="">
        </a>
        <a href="#!">
          <img src="../assets/imgs/footer/redes-yt.png" alt="">
        </a>
      </div>
      <div class="copy">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vitae interdum neque, nec dignissim dui. Suspendisse in sem gravida massa tempus convallis. Pellentesque volutpat, augue in scelerisque viverra, nisl diam tincidunt justo, scelerisque mollis elit odio ac eros. Mauris sed auctor lacus, vel pellentesque orci. Curabitur condimentum quam quis urna</p>
        <img src="../assets/imgs/footer/unilever.png" alt="">
      </div>
    </div>
  </div>
</template>

<style scoped>

.laco img {
  margin-top: 40px;
  z-index: 2;

}
.laco {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

hr {
  width: 95%;
  border: 1.5px solid;
  color: #FFF;
  opacity: 1;
  position: relative;
  top: -36px;
}
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.regulamento a {
  color: #FFF;
  text-decoration: none;
  font-family: brandon-grotesque;
  font-size: 18px;
}

p {
  font-size: 13px;
  text-align: center;
  color: #FFF;
}
.copy {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.regulamento {
  display: flex;
  width: 25%;
  flex-direction: row;
  justify-content: space-between;
}
.redes {
  display: flex;
  width: 40%;
  flex-direction: row;
  justify-content: space-around;
  margin-top: 30px;
  margin-bottom: 30px;
}
.container-fluid {
  background-color: #074A75;
  height: 45vh;
}
@media (max-width:991px) {
  .container-fluid {
    height: 100%;
  }
  .redes {
    width: 80%;
  }
  .regulamento {
    width: 70%;
  }
}
</style>
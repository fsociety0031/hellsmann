<template>
  <section class="container-fluid">
    <h2>DOS DRIBLES E ENTERRADAS MEMORÁVEIS AO ZERAR DO CRONÔMETRO,<br><strong>CADA HORA H DA NBA FICA MAIS SABOROSA COM HELLMANN'S.</strong><br>ASSISTA AO FILME ABAIXO:</h2>
    <div class="passos-wrapper">
      <iframe src="https://www.youtube.com/embed/KAIR1_wOJvg?si=KmKHPK3lVDC-pu1p" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
    </div>
  </section>
</template>
<style scoped>
h2 {
  font-family: 'brandon-grotesque';
  font-size: 40px;
  color: #FFF;
  text-align: center;
}

.passos-wrapper {
  max-width: 1010px;
  width: inherit;
  margin-top: 30px;
  display: flex;
  flex-direction: column;
  align-items: center;
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
  height: 110vh;
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  justify-content: flex-start;
  padding-top: 120px;
  padding-bottom: 53px;
  margin-top: -54px;
  align-items: center;
  margin-bottom: 22px;
}
iframe {
  width:881px;
  height:500px;
}
@media (max-width: 991px) {
  iframe {
    width: 100%;
    height: 100%;
  }
}
</style>
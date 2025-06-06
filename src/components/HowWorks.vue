<template>
  <div class="container">
    <div class="box">
      <img src="../assets/Img/app.png" class="app" />
      <img src="../assets/Img/app.png" class="app2" />
      <img src="../assets/Img/app.png" class="app3" />

      <div class="text-content">
        <div class="title">
          <h1>Como funciona o App</h1>
        </div>
        <div class="pa">
          <p class="paragraph">
            Com o QR Connect, tudo começa de forma <br /> simples: baixe o  
            aplicativo, faça seu cadastro <br /> e crie sua conta. personalizada de
            acordo <br /> com suas necessidades. Para participar de um evento, 
            será gerado um  QR Ticket exclusivo.<br /> Basta apresentá-lo na         
            entrada do evento e,<br /> após a validação, seu ingresso será
            <br /> confirmado — pronto! É só aproveitar a festa. 
          </p>
        </div>   
      </div>
    </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;400;500;700&display=swap');

.container {
  background-color: rgb(20, 20, 20);
  display: flex;
  justify-content: center;
  align-items: center;
}

.box {
  background-color: #1f1f1f;
  width: 150vh;
  height: 70vh;
  border-radius: 40px;
  position: relative; 
}

.app,
.app2,
.app3 {
  height: 600px;
  position: absolute;
  animation: floatUpDown 4s ease-in-out infinite;
}

.app {
  left: 6%;
  animation-delay: 0s;
  top: 10%;

}

.app2 {
  left: -10%;
  top: 0%;
  animation-delay: 1.3s;
  top: 10%;

}

.app3 {
  left: 22%;
  top: 0%;
  animation-delay: 2.6s;
  top: 10%;
}

@keyframes floatUpDown {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-15px);
  }
}

.text-content {
  text-align: start;
  padding-top: 65px;
}

.title {
  color: aliceblue;
  font-family: 'Roboto', sans-serif;
  padding-top: 40px;
  padding-left: 730px;
  font-size: 25px;
  text-align: center;
}

.pa {
  padding-top: 7px;
  padding-left: 750px;
}

.paragraph {
  color: aliceblue;
  font-size: 25px;
  padding-top: 50px;
  padding-right: 26px;
  text-align: center;
  padding-bottom: 10px;
  font-family: 'Roboto', sans-serif;
}

@media screen and (max-width: 1440px) {
  .box {
    width: 90vw;
    height: 90vh;
    padding: 40px 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .app{
    height: 550px;
    left: 30%;



  }

   .app2{
    height: 550px;
    left: 15%;


  }
   .app3{
    height: 550px;
    left: 45%;


  }



  .text-content {
    text-align: center;
    padding: 0 20px;
    padding-top: 400px;
  }

  .title {
    padding: 20px 0 10px;
    font-size: 24px;
  }

  .pa {
    padding: 0;
  }

  .paragraph {
    font-size: 18px;
    line-height: 1.6;
  }
}
@media screen and (max-width: 1024px) {
  .box {
    width: 90vw;
    height: 90vh;
    padding: 40px 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .app{
    height: 550px;
    left: 2%;
  }

   .app2{
    height: 550px;
    left: 24%;

  }
   .app3{
    height: 550px;
    left: 46%;

  }



  .text-content {
    text-align: center;
    padding: 0 20px;
    padding-top: 400px;
  }

  .title {
    padding: 20px 0 10px;
    font-size: 24px;
  }

  .pa {
    padding: 0;
  }

  .paragraph {
    font-size: 18px;
    line-height: 1.6;
  }
}

@media screen and (max-width: 768px) {
  .box {
    width: 90vw;
    height: 90vh;
    padding: 40px 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .app{
    height: 550px;
    left: -20%;
  }

   .app2{
    height: 550px;
    left: 12%;

  }
   .app3{
    height: 550px;
    left: 43%;

  }



  .text-content {
    text-align: center;
    padding: 0 20px;
    padding-top: 400px;
  }

  .title {
    padding: 20px 0 10px;
    font-size: 24px;
  }

  .pa {
    padding: 0;
  }

  .paragraph {
    font-size: 18px;
    line-height: 1.6;
  }
}

@media screen and (max-width: 425px) {
  .box {
    width: 90vw;
    height: 90vh;
    padding: 40px 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .app{
    height: 490px;
    left: -12%;
  }

   .app2{
    height: 0px;
    left: 12%;

  }
   .app3{
    height: 0px;
    left: 43%;

  }



  .text-content {
    text-align: center;
    padding: 0 20px;
    padding-top: 400px;
  }

  .title {
    padding: 20px 0 10px;
    font-size: 15px;
  }

  .pa {
    padding: 1;
  }

  .paragraph {
    padding-top: 15px;
    font-size: 14px;
    line-height: 1.7;
  }
}

@media screen and (max-width: 1440px) and (max-height: 585px) {
  .box {
    width: 95vw;
    height: 85vh;
    padding: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .app {
    height: 900px;
    left: 5%;
  }

  .app2 {
    height: 450px;
    left: 25%;
  }

  .app3 {
    height: 450px;
    left: 45%;
  }

  .text-content {
    padding-top: 340px;
    padding-left: 0;
    text-align: center;
  }

  .title {
    font-size: 22px;
    padding: 10px 0;
  }

  .pa {
    padding: 0;
  }

  .paragraph {
    font-size: 16px;
    line-height: 1.5;
  }
}
@media screen and (max-width: 1366px) {
  .container{
    padding-top: 20px;
  }
  .box {
    width: 95vw;
    height: 70vh;
    flex-direction: row;
    border-radius: 20px;
    display: flex;
    align-items: center;
  }

  .app,
  .app2,
  .app3 {
    position: absolute;
  }

  .app {
    height: 500px;
    top: -4%;
    left: -10%;
  }

  .app2 {
    height: 500px;
    top: -4%;
    left: 70%;

  }

  .app3 {
    display: none;
  }

  .text-content {
    padding: 0 10px;
    position: absolute;
    text-align: center;
    width: 100%;
  }

  .title {
    padding-top: 10px;
    font-size: 22px;
    line-height: 1.4;
  }

  .pa {
    padding-left: 0;
  }

  .paragraph {
    font-size: 16px;
    line-height: 1.6;
    margin-bottom: 10px;
  }

  .button-position {
    padding-top: 10px;
  }

  .download {
    padding: 1rem 1.5rem;
    flex-direction: row;
    gap: 0.75rem;
  }

  .download-icon {
    width: 40px;
    height: 40px;
  }

  .download-info h2 {
    font-size: 18px;
  }

  .download-info p {
    font-size: 14px;
  }
}

</style>

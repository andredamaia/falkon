<template> 
  <div>
    <div id="app">
      <header>
        <div class="logo">
          <img src="./assets/logo.png" alt="falkon">
        </div>
      </header>

    <div class="banner">
      <div class="container">
        <div class="row">
          <div class="md-12 col md-12">
            <h1>O MELHOR CENTRO DE GAMES <p>DE JOINVILLE</p></h1>
                <a class="button-blue" href="#" >Aluguel para eventos</a>
            
                <a class="button-white" href="#">Reservar horário avulso</a>
          </div>
        </div>
      </div>
    </div>

    <div class="title-black">
      <div class="container">
        <div class="row">
          <div class="md-12 col md-12">
            <H2> <small>ALUGUEL PARA EVENTOS</small> <p> VENHA COMEMORAR O SEU ANIVERSÁRIO </p> <p>NA FALKON SPACE </p></H2>
          </div>
        </div>
      </div>
    </div>

    <div class="bg-black">
      <div class="container">
        <div class="row">
          <div class="md-12 col-md-4">
            <img src="./assets/aluguel-1.jpg" alt="">
          </div>

          <div class="md-12 col-md-4">
            <img src="./assets/aluguel-2.jpg" alt="">
          </div>

          <div class="md-12 col-md-4">
            <img src="./assets/aluguel-3.jpg" alt="">
          </div>
        </div>
      </div>

      <div class="container">
        <div class="row">
          <div class="md-12 col-md-7">
            <p>Nada melhor do que curtir o seu aniversário com os amigos jogando o seu jogo favorito nos melhores setups gamers</p>
            <p>São 10 computadores de alta performance, um super simulador de corrida com movimentos e 2 playstation 4 com realidade virtual em uma área de 150m²</p>
            <a href="#">QUERO FAZER MEU EVENTO</a>
          </div>

          <div class="md-12 col md-5">
            <table>
              <tr>
                <td>DURAÇÃO DO EVENTO</td>
                <td>PREÇO</td>
              </tr>

              <tr>
                <td>1 hora durante a semana</td>
                <td>R$120</td>
              </tr>

              <tr>
                <td>1 hora fim de semana</td>
                <td>R$150</td>
              </tr>

              <tr>
                <td>5 horas durante a semana</td>
                <td>R$550</td>
              </tr>

              <tr>
                <td>5 horas durante o final de semana</td>
                <td>R$750</td>
              </tr>
            </table>
          </div>
        </div>
      </div>
    </div>
  </div>
  </div>
</template>


<script>
export default{
  name: 'app'
}
</script>

<style>

@import url('https://fonts.googleapis.com/css?family=Roboto:100,100i,300,300i,400,400i,500,500i,700,700i,900,900i&display=swap');

  .logo{
    background: #000000;
    text-align: center;
    padding: 25px 0;
    
  }

  .banner{
  background: url('./assets/banner.jpg');
  display:flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 150vh;
  text-align: center;
  
  }

  

  .banner h1{
    font-size: 54px;
    color: #ffffff;
    text-align: center;
    position: block;
    padding: 12px 25px;
    line-height: 5px;
  }

  .button-blue {
    color: #ffffff;
    font-size: 21px;
    border-style: 30px;
    background: #0061f3;
    padding: 15px 15px;
    align-items: center;
    border-top: 0;
    border-right: 0;
    border-left: 0;
    text-decoration: none;
    justify-content: center;
    display: inline-block;
    margin: 0 30px;
  
  }

  .button-white{
    color: #0061f3;
    font-size: 21px;
    border-style: 30px;
    background: #ffffff;
    padding: 15px 15px;
    align-items: center;
    border-top: 0;
    border-right: 0;
    border-left: 0;
    text-decoration: none;
    justify-content: center;
    display: inline-block;
  }
</style>

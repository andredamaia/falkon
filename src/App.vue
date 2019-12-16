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
            <div class="col-12 col-md-12">
              <h1>O melhor centro de games <br /> de Joinville</h1>

              <a class="button-blue" href="#" >Aluguel para eventos</a>
              <a class="button-white" href="#">Reservar horário avulso</a>
            </div>
          </div>
        </div>
      </div>

      <div class="bg-black">
        <div class="container">
          <div class="row">
            <div class="col-12 text-center">
              <h2>
                <small>Aluguel para eventos</small>
                venha comemorar o seu aniversário <br />  na Falkon Space
              </h2>
            </div>

            <div class="col-12 col-md-4">
              <img class="img-black" src="./assets/aluguel-1.jpg" alt="">
            </div>

            <div class="col-12 col-md-4">
              <img class="img-black" src="./assets/aluguel-2.jpg" alt="">
            </div>

            <div class="col-12 col-md-4">
              <img class="img-black" src="./assets/aluguel-3.jpg" alt="">
            </div>

            <div class="col-12 col-md-6">
              <p>Nada melhor do que curtir o seu aniversário com os amigos jogando o seu jogo favorito nos melhores setups gamers</p>
              <p>São 10 computadores de alta performance, um super simulador de corrida com movimentos e 2 playstation 4 com realidade virtual em uma área de 150m²</p>
              
              <a href="#" class="button-blue">Quero fazer meu evento</a>
            </div>

            <div class="col-12 col-md-5 offset-md-1">
              <table>
                <tr>
                  <th>Duração do Evento</th>
                  <th>Preço</th>
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

            <div class="col-12 text-center">
              <h3>Perguntas Frequentes</h3>
            </div>

            <div class="col-12 col-md-6">
              <div class="box-question" v-on:click="active = !active" v-bind:class="{ active: false }">
                  <div class="question-header">
                    Posso levar comida e bebida?

                    <span><img src="./assets/icon-arrow.png" alt="" /></span>
                  </div>

                  <div class="question-body" style="display: none;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec et arcu pretium, tincidunt mi vel, tincidunt tellus. Vestibulum accumsan dolor quis mi tempor, et tempus mi tempor. Sed hendrerit ligula et tempus ultricies. Donec nibh lectus, volutpat in lectus aliquam, ornare tristique augue.</div>
              </div>

              <div class="box-question">
                  <div class="question-header">
                    O que está incluso no valor?

                    <span><img src="./assets/icon-arrow.png" alt="" /></span>
                  </div>

                  <div class="question-body">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec et arcu pretium, tincidunt mi vel, tincidunt tellus. Vestibulum accumsan dolor quis mi tempor, et tempus mi tempor. Sed hendrerit ligula et tempus ultricies. Donec nibh lectus, volutpat in lectus aliquam, ornare tristique augue.</div>
              </div>
            </div>

            <div class="col-12 col-md-6">
              <div class="box-question">
                  <div class="question-header">
                    Quais equipamentos estarão disponíveis?

                    <span><img src="./assets/icon-arrow.png" alt="" /></span>
                  </div>

                  <div class="question-body" style="display: none;">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec et arcu pretium, tincidunt mi vel, tincidunt tellus. Vestibulum accumsan dolor quis mi tempor, et tempus mi tempor. Sed hendrerit ligula et tempus ultricies. Donec nibh lectus, volutpat in lectus aliquam, ornare tristique augue.</div>
              </div>

              <div class="box-question">
                  <div class="question-header">
                    Quantas pessoas podem participar da festa?

                    <span><img src="./assets/icon-arrow.png" alt="" /></span>
                  </div>

                  <div class="question-body">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec et arcu pretium, tincidunt mi vel, tincidunt tellus. Vestibulum accumsan dolor quis mi tempor, et tempus mi tempor. Sed hendrerit ligula et tempus ultricies. Donec nibh lectus, volutpat in lectus aliquam, ornare tristique augue.</div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="bg-game">
        <div class="container">
          <div class="row">
            <div class="col-12 text-center">
              <h2>
                <small>Games disponíveis</small>
                Os melhores games para você curtir com <br /> os seus amigos
              </h2>

              <div class="games-holder">
                <div class="box-game">
                  <img src="./assets/jogo-1.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-2.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-3.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-4.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-5.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-6.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-7.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-8.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-9.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-10.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-11.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-12.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-13.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-14.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-15.jpg" alt="" />
                </div>

                <div class="box-game">
                  <img src="./assets/jogo-16.jpg" alt="" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="bg-black">
        <div class="container">
          <div class="row">
            <div class="col-12 col-md-3">
              <div class="box-icon">
                <img src="./assets/icon-1.png" alt="" />

                <p>Playstation 4 + óculos de <br /> realidade virtual</p>
              </div>
            </div>

            <div class="col-12 col-md-3">
              <div class="box-icon">
                <img src="./assets/icon-2.png" alt="" />

                <p>Simulador de corrida <br /> profissional</p>
              </div>
            </div>

            <div class="col-12 col-md-3">
              <div class="box-icon">
                <img src="./assets/icon-3.png" alt="" />

                <p>Computadores de alta <br /> performance</p>
              </div>
            </div>

            <div class="col-12 col-md-3">
              <div class="box-icon">
                <img src="./assets/icon-4.png" alt="" />

                <p>100 MB - internet de <br /> fibra ótica</p>
              </div>
            </div>
          </div>
        </div>
      </div>


      <div class="bg-game">
        <div class="container">
          <div class="row">
            <div class="col-12 text-center">
              <h2>
                <small>Reservas</small>
                Valores e horários disponíveis
              </h2>
            </div>

            <div class="col-12 col-md-7">
              <table cellspacing="3" cellpadding="3">
                <tr>
                  <th>Equipamento</th>
                  <th>Preço</th>
                  <th>Tempo</th>
                </tr>
                <tr>
                  <td>Simulador de corrida profissional</td>
                  <td>R$ 15</td>
                  <td>Corrida</td>
                </tr>
                <tr>
                  <td>Playstation 4 + Realidade virtual</td>
                  <td>R$ 5</td>
                  <td>1 Hora</td>
                </tr>
                <tr>
                  <td>Playstation 4 + Realidade virtual</td>
                  <td>R$ 12</td>
                  <td>3 Horas</td>
                </tr>
                <tr>
                  <td>Computadores</td>
                  <td>R$ 7</td>
                  <td>1 Hora</td>
                </tr>
                <tr>
                  <td>Computadores</td>
                  <td>R$ 18</td>
                  <td>3 Horas</td>
                </tr>
              </table>
            </div>

            <div class="col-12 col-md-4 offset-md-1">
              <table>
                <tr>
                  <th>Horário de funcionamento</th>
                  <th></th>
                </tr>
                <tr>
                  <td>Sexta à domingo</td>
                  <td>10h às 23h</td>
                </tr>
              </table>

              <a href="#" class="button-blue">Reservar horário</a>
            </div>
          </div>
        </div>
      </div>


      <div class="bg-black">
        <div class="container">
          <div class="row">
            <div class="col-12 text-center">
              <h2>
                <img src="./assets/icon.png" alt="" /><br /> 
                Corujão Falkon Space
              </h2>
            </div>

            <div class="col-12 col-md-6">
              <p>Reúna seus amigos e venha fazer um corujão com equipamentos de primeira em um ambiente super confortável.</p>

              <p>Você pode fazer sua reserva através do WhatsApp da Falkon Space.</p>
            </div>

            <div class="col-12 col-md-4 offset-md-2">
              <table>
                <tr>
                  <th>Horário</th>
                  <th>Preço</th>
                </tr>
                <tr>
                  <td>22h00 às 06h30</td>
                  <td>R$ 40</td>
                </tr>
              </table>

              <a href="#" class="button-blue">Agendar corujão</a>
            </div>
          </div>
        </div>
      </div>

      <footer>
        <div class="container">
          <div class="row">
            <div class="col-12 text-center">
              <img src="./assets/logo.png" width="280" style="margin-bottom: 80px;" alt="" />
            </div>

            <div class="col-12 col-md-3">
              <h5>Endereço</h5>

              <p>
                Rua Guanabara, 796 <br />
                Bairro Guanabara <br />
                Joinville / Santa Catarina
              </p>
            </div>

            <div class="col-12 col-md-3">
              <h5>Telefone</h5>

              <p>(47) 3271-1516</p>
            </div>

            <div class="col-12 col-md-3">
              <h5>WhatsApp</h5>

              <p>(47) 99904-9902</p>
            </div>

            <div class="col-12 col-md-3">
              <h5>Redes Sociais</h5>

              <a href="https://www.instagram.com/falkon.space/" target="_blank" class="link-social">
                <img src="./assets/icon-instagram.png" alt="" />
                falkon.space
              </a>

              <a href="https://www.facebook.com/Falkon.Space/?ref=br_rs" target="_blank" class="link-social">
                <img src="./assets/icon-facebook.png" alt="" />
                falkon.space
              </a>
            </div>
          </div>
        </div>

        <div class="container copyright">
          <div class="row">
            <div class="col-12">
              <hr />
            </div>

            <div class="col-12 col-md-6">
              <p>© Falkon Space - Todos os diretos reservados	</p>
            </div>

            <div class="col-12 col-md-6 text-right">
              <p>
                Desenvolvido por <a href="#">B3 MARKETING</a>
              </p>
            </div>
          </div>
        </div>
      </footer>

    </div>
  </div>
</template>

<script defer type="text/javascript">
  import 'bootstrap/dist/css/bootstrap.css'

  export default{
    name: 'app',
  }
</script>

<style>

  @import url('https://fonts.googleapis.com/css?family=Roboto:100,100i,300,300i,400,400i,500,500i,700,700i,900,900i&display=swap');
  @import url('https://fonts.googleapis.com/css?family=Poppins:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i&display=swap');


  * {
    margin: 0;
    padding: 0;
    outline: 0;
    box-sizing: border-box;
  }

  html, body, #root {
    min-height: 100%;
  }

  body { -webkit-font-smoothing: antialiased !important; }

  body, input, button {
    font-family: 'Roboto', Arial, Helvetica, sans-serif;
  }

  p { margin-bottom: 30px; }

  table { width: 100%; }
  th { color: #fff; font-size: 21px; border-bottom: 1px solid #0061f3; padding: 15px 0; }
  tr td { border-bottom: 1px solid #0061f3; padding: 15px 0; color: #a8a7a7; font-size: 21px; }
  table tr:last-child td { border-bottom: none; }

  h1 {
    font-family: 'Poppins', sans-serif;
    font-size: 54px;
    font-weight: 700;
    margin-bottom: 90px;
    color: #fff;
    line-height: 60px;
    letter-spacing: 2px;
    text-transform: uppercase;
  }

  h2 {
    color: #fff;
    font-family: 'Poppins', sans-serif;
    font-size: 36px;
    font-weight: 600;
    margin-bottom: 60px;
    text-transform: uppercase;
  }
    h2 small {
      color: #0061f3;
      font-size: 18px;
      text-transform: uppercase;
      letter-spacing: 4px;
      font-weight: 400;
      display: block;
      margin-bottom: 20px;
    }

  h3 {
    color: #fff;
    font-family: 'Poppins', sans-serif;
    font-size: 28px;
    font-weight: 600;
    margin-bottom: 60px;
    text-transform: uppercase;
    margin-top: 120px;
  }

  h5 { color: #fff; font-size: 21px; margin-bottom: 10px; }

  p {
    color: #fff;
    font-size: 21px;
    opacity: .6;
  }

  .container { max-width: 1200px; }

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
    min-height: 85vh;
    text-align: center;
  }
  .banner .button-blue { margin-right: 30px; }

  .button-blue {
    color: #ffffff;
    font-size: 21px;
    border-style: 30px;
    background: #0061f3;
    padding: 15px 30px;
    align-items: center;
    border-top: 0;
    border-right: 0;
    border-left: 0;
    text-decoration: none;
    justify-content: center;
    display: inline-block;
    transition: all .3s ease-in-out;
  }
    .button-blue:hover { 
      background: #0b449a; 
      box-shadow: 0 0 20px rgba(32,102,208,.3); 
      color: #fff; 
      text-decoration: none; 
    }

  .button-white {
    color: #0061f3;
    font-size: 21px;
    border-style: 30px;
    background: #ffffff;
    padding: 15px 30px;
    align-items: center;
    border-top: 0;
    border-right: 0;
    border-left: 0;
    text-decoration: none;
    justify-content: center;
    display: inline-block;
    transition: all .3s ease-in-out;
  }
    .button-white:hover { 
      background: #fff; 
      box-shadow: 0 0 20px rgba(255,255,255,.3); 
      color: #0061f3; 
      text-decoration: none; 
    }

  .title-black{
    background: #000000;
    text-align: center;
    padding: 80px 0;
  }

  .title-black small{
    color: #0061f3;
    text-align: center;
  }

  .title-black p {
    color: #ffffff;
    text-align: center;
  }

  .title-black h2{
    font-size: 36px;
    line-height: 0;
  }

  .title-black small{
    font-size: 21px;
  }

  .bg-black {
    padding: 120px 0;
    background: #060606 !important;
  }

  .img-black {
    max-width: 100%;
    margin-bottom: 50px;
  }

  .bg-game {
    padding: 120px 0;
    background: url(./assets/bg.png) center center no-repeat;
    background-size: cover;
  }

  .games-holder { display: flex; flex-direction: row; justify-content: center; align-items: center; flex-wrap: wrap; }
  .box-game { padding: 10px; width: 12.5%; }
  .box-game img { max-width: 100%; transition: all .3s ease-in-out; position: relative; }
  .box-game:hover img { transform: scale(1.15); box-shadow: 0 5px 20px rgba(0,0,0,.5); z-index: 10; }

  .box-icon {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    text-align: center;
  }
  .box-icon img { margin-bottom: 30px; }

  table { margin-bottom: 30px; }

  footer { padding: 120px 0 20px; background: #121112; }
  footer hr { border-top: 1px solid #abaaab; }
  
  .copyright p { font-size: 16px; }
  .copyright a { color: #fff; font-weight: 600; }

  .link-social { color: #a8a7a7; font-size: 16px; display: block; margin-bottom: 10px; }
  .link-social img { margin-right: 10px; }

  .box-question { border: 1px solid #3d3b3b; padding: 20px; cursor: pointer; margin-bottom: 10px; }
  .question-header { font-size: 21px; color: #b7b7b7; position: relative; }
  .question-header span { position: absolute; top: 0; right: 10px; }

  .question-body { display: none; margin-top: 15px; }


@media (max-width: 948px){
  
  .banner .button-blue {
    margin-right: 25px;
    margin-bottom: 20px;
    margin-left: 25px;
  }

  .banner h1{
    font-size: 35px;
    line-height: 42px;
    margin-bottom: 90px;
    letter-spacing: 1px;
    font-weight: 600;
  }

  .bg-game{

    padding: 90px 0;
    
    }

  .bg-game table tr td{
    padding: 16px 7px;
    font-size: 15px;
  }

  .bg-game th{
    font-size: 18px;
  }
  
  .bg-game h2{
    font-size: 27px;
  }

  .bg-game .button-blue{
    padding: 15px 15px;
    width: 100%;
    text-align: center;
  }

  .games-holder .box-game{
    width: 25%;
  }

  .bg-black{
    padding: 70px 0;
  }

  .bg-black h2{
    font-size: 30px;
  }

  .bg-black h3{
    margin-top: 45px;
  }

  .bg-black .button-blue{
    padding: 15px 15px;
    width: 100%;
    text-align: center;
    margin: 30px 0;
  }

  .bg-black p {
     margin-bottom: 20px;
  }

  .question-header {

    font-size: 15px;
  }

  .button-blue{

  padding: 15px 43px;
  }

  footer{
    padding: 80px 0 20px;
    text-align: center;
  }

  footer .text-right {
    text-align: center !important;
}

}




</style>



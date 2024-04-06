<!DOCTYPE html>

<html>
<head>
  <meta http-equiv="CONTENT-TYPE" content="text/html; charset=UTF-8">
  <title>Te amo</title>
  <style>
  
 
  body{
    background-color: pink;
  }
  .painel{
    margin: auto;
    background-color: white;
    width: 500px;
    height: 800px;
    border-radius: 50px;
    text-align: center;
    padding-top: 50px;
    font-family:'Franklin Gothic Medium', Arial, sans-serif;
  }
  #sim{
    text-align: center;
    height: 70px;
    width: 100px;
    background-color: green;
    border: 2px solid white;
    border-radius: 100px;
    color: white;
    margin-left: -95px;
    
    
  }
 #nao{
   position: absolute;
   height: 70px;
    width: 100px;
    background-color: red;
    border: 2px solid white;
    border-radius: 100px;
    color: white;
   margin-left: 10px;
 }
  </style>



<div class="painel"> <h1>
  
  
    O SEU SORRISO É UMA OBRA DE ARTE TÃO PERFEITA QUE ATÉ VAN GOGH BATERIA PALMAS!❤
   
  </h1><h1>Aceita namorar comigo?❤</h1>
  
  
  <img src="https://tenor.com/pt-BR/view/hinata-naruto-kiss-kissing-sweet-gif-17077533.gif" alt="">
  <button id="sim" onclick="parabens()"> Sim! </button>
  <button onclick="fuja()" id="nao"> Não! </button>
  
  </div>  

 <script>
function fuja(){
  var botaoNao = document.getElementById("nao")
  
  var larguraJanela = window.innerWidth;
  var alturaJanela = window.innerHeight;
  
  var maxX = larguraJanela - botaoNao.offsetWidth;
  var maxY = alturaJanela - botaoNao.offsetHeight;
  
  var aleatorioX = Math.floor(Math.random() * maxX);
  var aleatorioY = Math.floor(Math.random() * maxY);
  
  botaoNao.style.left = aleatorioX + "px";
  botaoNao.style.top = aleatorioY + "px";
}

function parabens(){
  alert("Não acredito que você aceitou. Saiba que eu fico muito feliz com isso, pois desde o dia em que te vi, eu me apaixonei por você. O conforto que sinto quando estamos em silêncio, juntinhos, me faz amar o pequeno universo que construímos para nós. Quero estar com você a cada momento. TE AMOO!")
}

</script>
</div>
</head>
<body>
</body>
</html>

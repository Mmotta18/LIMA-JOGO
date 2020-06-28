<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width-device-width, initial-scale-1.0">
        <link rel="stylesheet" href="main.css">
        <script src="script.js" async></script>
        <title>Jogo da Memoria</title>
    </head>
    <body>
       <h1 class="titulo">Jogo da Memória</h1>
       <div class="overlay-text visible">
           Clique para iniciar
       </div>
       <div id="game-over-text" class="overlay-text">
        VOCÊ PERDEU
        <span class="overlay-text-small">Clique para reiniciar</span>
    </div>
    <div id="win-text" class="overlay-text">
        VOCÊ GANHOU
        <span class="overlay-text-small">Clique para reiniciar</span>
    </div>
       <div class="container-jogo">
           <div class="container-info-jogo">
               <div class="info-jogo">
                   Tempo <span id="tempo-restante">100</span>
               </div>
               <div class="info-jogo">
                Flips <span id="tentativas">0</span>
            </div>
           </div>
           <div class="card">
               <div class="costas face">
               <img class="duvida" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Question_mark.png" width="50%" alt="">
               </div>
               <div class="frente face">
                   <img class="card-value" src="https://image.freepik.com/free-vector/cute-elephant-cartoon_160606-195.jpg" width="100%" alt="ELEFANTE">
               </div>
           </div>
           <div class="card">
            <div class="costas face">
            <img class="duvida" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Question_mark.png" width="50%" alt="">
            </div>
            <div class="frente face">
                <img class="card-value" src="https://image.freepik.com/free-vector/cute-elephant-cartoon_160606-195.jpg" width="100%" alt="ELEFANTE">
            </div>
        </div>
        <div class="card">
            <div class="costas face">
            <img class="duvida" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Question_mark.png" width="50%" alt="">
            </div>
            <div class="frente face">
                <img class="card-value" src="https://image.freepik.com/free-vector/cartoon-happy-lion-isolated-white-background_29190-752.jpg" width="100%" alt="LEAO">
            </div>
        </div>
        <div class="card">
            <div class="costas face">
            <img class="duvida" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Question_mark.png" width="50%" alt="">
            </div>
            <div class="frente face">
                <img class="card-value" src="https://image.freepik.com/free-vector/cartoon-happy-lion-isolated-white-background_29190-752.jpg" width="100%" alt="LEAO">
            </div>
        </div>
        <div class="card">
            <div class="costas face">
            <img class="duvida" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Question_mark.png" width="50%" alt="">
            </div>
            <div class="frente face">
                <img class="card-value" src="https://image.freepik.com/free-vector/cute-giraffe-cartoon-isolated-white-background_29190-4965.jpg" width="100%" alt="GIRRAFA">
            </div>
        </div>
        <div class="card">
            <div class="costas face">
            <img class="duvida" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Question_mark.png" width="50%" alt="">
            </div>
            <div class="frente face">
                <img class="card-value" src="https://image.freepik.com/free-vector/cute-giraffe-cartoon-isolated-white-background_29190-4965.jpg" width="100%" alt="GIRRAFA">
            </div>
        </div>
        <div class="card">
            <div class="costas face">
            <img class="duvida" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Question_mark.png" width="50%" alt="">
            </div>
            <div class="frente face">
                <img class="card-value" src="https://image.freepik.com/free-vector/cute-monkey-cartoon_146562-7.jpg" width="110%" alt="MACACO">
            </div>
        </div>
        <div class="card">
            <div class="costas face">
            <img class="duvida" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Question_mark.png" width="50%" alt="">
            </div>
            <div class="frente face">
                <img class="card-value" src="https://image.freepik.com/free-vector/cute-monkey-cartoon_146562-7.jpg" width="110%" alt="MACACO">
            </div>
        </div>
        <div class="card">
            <div class="costas face">
            <img class="duvida" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Question_mark.png" width="50%" alt="">
            </div>
            <div class="frente face">
                <img class="card-value" src="https://image.freepik.com/free-vector/cute-turtle-cartoon_33070-3103.jpg" width="100%" alt="TARTARUGA">
            </div>
        </div>
        <div class="card">
            <div class="costas face">
            <img class="duvida" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Question_mark.png" width="50%" alt="">
            </div>
            <div class="frente face">
                <img class="card-value" src="https://image.freepik.com/free-vector/cute-turtle-cartoon_33070-3103.jpg" width="100%" alt="TARTARUGA">
            </div>
        </div>
        <div class="card">
            <div class="costas face">
            <img class="duvida" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Question_mark.png" width="50%" alt="">
            </div>
            <div class="frente face">
                <img class="card-value" src="https://image.freepik.com/free-vector/bear-cartoon_119631-97.jpg" width="100%" alt="URSO">
            </div>
        </div>
        <div class="card">
            <div class="costas face">
            <img class="duvida" src="https://upload.wikimedia.org/wikipedia/commons/a/af/Question_mark.png" width="50%" alt="">
            </div>
            <div class="frente face">
                <img class="card-value" src="https://image.freepik.com/free-vector/bear-cartoon_119631-97.jpg" width="100%" alt="URSO">
            </div>
        </div>
       </div>
    </body>
</html>

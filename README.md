<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
       <link rel="stylesheet" href="css/style.sheet"> 
    </head>
    <body>
        <h1>Rock Paper Scissors!</h1>
        <div class='score-div'>Player <span id='playerScore'></span> - <span id='computerScore'></span> Computer</div>
        <div class='text'><span id='pSelection'></span> vs <span id='cSelection'></span></div>
        <div class='text' id = 'choose-msg' >Choose your weapon: </div>
        <div class="rps-container">
            <button class="rps-btn" id="rock"> <img src="https://icons.veryicon.com/128/System/Icons8%20Metro%20Style/Rock%20Paper%20Scissors%20Rock.png"></button>
            <button class="rps-btn" id="paper"><img src="https://icons.veryicon.com/128/System/Icons8%20Metro%20Style/Rock%20Paper%20Scissors%20Paper.png"></button>
            <button class="rps-btn" id="scissors"><img src="https://icons.veryicon.com/128/System/Icons8%20Metro%20Style/Rock%20Paper%20Scissors%20Scissors.png"></button>
        </div>
        <div class='text' id='message'></div>
        <div class='text' id='finalResult'></div>
    </body>
</html>

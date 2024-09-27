<h1 align="centre">Roblox Minesweeper</h1>
Roblox minesweeper game generator.
<br>Minesweeper is a classic single-player puzzle game where the objective is to clear a grid of hidden mines without detonating them. The player uncovers squares, and if a square doesn't contain a mine, it reveals a number indicating how many mines are adjacent to it. Using logic and deduction, the player must flag potential mines and avoid touching them while uncovering all other safe squares to win the game. If a mine is touched, the game is over.
<br>This is very basic minesweeper generator. I have only attached the game-generator script. You can spawn the game at any position by passing the size and starting position in the Minesweeper function. <br>
<video width="500px" 
           height="400px" 
           controls="controls">
        <source src=
"/sampleVideo" 
                type="video/mp4" />
    </video>
<h1 align="centre">Exploiter Prevention</h1>
I have put a few countermeasures against exploiters in the game. These are:
<li>Every block is identical. Meaning no one can tell the difference between a bomb and a normal block without touching it.</li>
<li>The GUI that displays number of bombs around a safe box is present in each and every box and is randomised for bombs and boxes have no bombs around them. Meaning if an exploiter tries to learn the numbers beforehand messing with the Visible property of the GUI, he will be misguided.</li>
<li>You can set it so that only one or all players are able to interact with the tiles. This is helpful in preventing sabotaging.</li>
<h1 align="centre">How to use</h1>
Using this module is quite easy. Here are a few steps:
<li>Copy the code and put it in a module script</li>
<li>require the module script in a ServerScript using require([module location goes here])</li>
<li>following code will run spawn the game: module.mineSweeper(size:number, pos:Vector3, player:Player)</li>
<ul><li>Here, size is the number of rows and coloumns, pos is the position where the game will spawn, and player reffers to the only player allowed to interact with the tiles. Setting player = nil will make it so that all players can interact with the minesweeper game.</li></ul>
<li>You can just download the Minesweeper.rblx file and try it there</li>

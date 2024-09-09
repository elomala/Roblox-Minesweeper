# Roblox-Minesweeper
Roblox minesweeper game generator.
<br>Minesweeper is a classic single-player puzzle game where the objective is to clear a grid of hidden mines without detonating them. The player uncovers squares, and if a square doesn't contain a mine, it reveals a number indicating how many mines are adjacent to it. Using logic and deduction, the player must flag potential mines and avoid touching them while uncovering all other safe squares to win the game. If a mine is touched, the game is over.
<br>This is very basic minesweeper generator. I have only attached the game-generator script. You can spawn the game at any position by passing the size and starting position in the Minesweeper function.
# Exploiter-Prevention
I have put a few countermeasures against exploiters in the game. These are:
<li>Every block is identical. Meaning no one can tell the difference between a bomb and a normal block without touching it.</li>
<li>The GUI that displays number of bombs around a safe box is present in each and every box and is randomised for bombs and boxes have no bombs around them. Meaning if an exploiter tries to learn the numbers beforehand messing with the Visible property of the GUI, he will be misguided.</li>
<li></li>

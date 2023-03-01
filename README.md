# Battleship-Game
Uses Programming Fundamentals only. It was my Final project of the programming Fundamentals Course.

Working: Two players each will first place their battleships on a grid (2 grids will have their specific ship placements) and then turn by turn they will have to guess where a battleship is placed on the grid (their guesses will each have a separate grid as well). Whoever guesses the others ships first will win. The guessing board of first player will be compared with placed ships of the second player which is how the flow of the code goes. The 'instructions()' function explains how the game works as well you can run the game and enter the instructions option to see it as well.

The working is not very complicated which many might assume from the length of the code.
The only reason the code is that big is because 4 different boards are used according to the difficulty level so easy mode has 4 tables same with medium and hard so each function had to perform the same working but with minor variable changes.

The working is explained in the comments of the 'player_vs_player_easy()' function which stays the same in all of the game modes except that arrays will be iterated according to their board size. Toss decides who gets to go first. 

note: Player vs machine mode hasn't been integrated so it works the same as player vs player mode

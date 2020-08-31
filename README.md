# TeekoGame
User can play teeko board game with AI opponent.\
AI opponent is implemented by MiniMax algorithm.

## How to play Teeko
![](https://github.com/YeochanYoun119/TeekoGame/blob/master/20200831_005723.jpg?raw=true)\
It is a game between two players on a 5x5 board. Each player has four markers of either **red or black**.
Beginning with black, they take turns placing markers (the "drop phase") until all markers are on the
board, with the goal of getting four in a row horizontally, vertically, or diagonally, or in a 2x2 box as
shown above.\
If after the drop phase neither player has won, they continue taking turns moving one marker at a time—
to an adjacent space only!—until one player wins.

# MiniMax algorithm

# Run
```
0:           
1:           
2:           
3:           
4:           
   A B C D E
b moved at A0
0: b         
1:           
2:           
3:           
4:           
   A B C D E
r's turn
Move (e.g. B3): C1
0: b         
1:     r     
2:           
3:           
4:           
   A B C D E
b moved at D1
0: b         
1:     r b   
2:           
3:           
4:           
   A B C D E
r's turn
Move (e.g. B3): D2
0: b         
1:     r b   
2:       r   
3:           
4:           
   A B C D E
b moved at B2
0: b         
1:     r b   
2:   b   r   
3:           
4:           
   A B C D E
r's turn
Move (e.g. B3): E3
0: b         
1:     r b   
2:   b   r   
3:         r 
4:           
   A B C D E
b moved at B0
0: b b       
1:     r b   
2:   b   r   
3:         r 
4:           
   A B C D E
r's turn
Move (e.g. B3): D3
0: b b       
1:     r b   
2:   b   r   
3:       r r 
4:           
   A B C D E
b moved from B2
  to B1
0: b b       
1:   b r b   
2:       r   
3:       r r 
4:           
   A B C D E
r's turn
Move from (e.g. B3): C1
Move to (e.g. B3): C2
0: b b       
1:   b   b   
2:     r r   
3:       r r 
4:           
   A B C D E
b moved from D1
  to D0
0: b b   b   
1:   b       
2:     r r   
3:       r r 
4:           
   A B C D E
r's turn
Move from (e.g. B3): C2
Move to (e.g. B3): C1
0: b b   b   
1:   b r     
2:       r   
3:       r r 
4:           
   A B C D E
b moved from B1
  to C0
0: b b b b   
1:     r     
2:       r   
3:       r r 
4:           
   A B C D E
AI wins! Game over.
```

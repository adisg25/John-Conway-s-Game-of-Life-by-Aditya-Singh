# John-Conway-s-Game-of-Life-by-Aditya-Singh
# https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life
This is the code for the John Conway Game of Life in C langauge where initial stage is taken as input and based on game rules next stage is show as output.

Rules:
1. Any live cell with two or three live neighbours survives.
2. Any dead cell with three live neighbours becomes a live cell.
3. All other live cells die in the next generation. Similarly, all other dead cells stay dead.

If the value of call is "1", it means cell is alive else it will be "0" which means cell is dead.

Input/Initial Stage:
 ----- ----- ----- -----
:  1  :  1  :  0  :  0  :
 ----- ----- ----- -----
:  1  :  0  :  0  :  0  :
 ----- ----- ----- -----
:  0  :  0  :  1  :  1  :
 ----- ----- ----- -----
:  1  :  1  :  1  :  1  :
 ----- ----- ----- -----
:  1  :  0  :  1  :  0  :
 ----- ----- ----- -----

 Output/Next Stage:
 ----- ----- ----- -----
:  1  :  1  :  0  :  0  :
 ----- ----- ----- -----
:  1  :  0  :  1  :  0  :
 ----- ----- ----- -----
:  1  :  0  :  0  :  1  :
 ----- ----- ----- -----
:  1  :  0  :  0  :  0  :
 ----- ----- ----- -----
:  1  :  0  :  1  :  1  :
 ----- ----- ----- -----

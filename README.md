# Snake-and-Ladder-Hackerrank
Markov takes out his Snakes and Ladders game and stares at the board, and wonders: If he had absolute control on the die, and could get it to generate any number (in the range 1-6) he desired, what would be the least number of rolls of the die in which he'd be able to reach the destination square (Square Number 100) after having started at the base square (Square Number 1)? 
<br>
Rules:<br>
1.Markov has total control over the die and the face which shows up every time he tosses it. You need to help him<br> figure out the minimum number of moves in which he can reach the target square (100) after starting at the base <br>
(Square 1).<br>
<br>
2.A die roll which would cause the player to land up at a square greater than 100, goes wasted, and the player<br>
remains at his original square. Such as a case when the player is at Square Number 99, rolls the die, and ends up<br>
with a 5.<br>
<br>
3.If a person reaches a square which is the base of a ladder, (s)he has to climb up that ladder, and he cannot come<br>
down on it. If a person reaches a square which has the mouth of the snake, (s)he has to go down the snake and come<br> out through the tail - there is no way to climb down a ladder or to go up through a snake.<br>
<br>
Input Format<br>
<br>
The first line contains the number of tests, T. T testcases follow.<br>
<br>
For each testcase, the first line contain N(Number of ladders) and after that N line follow. Each of the N line<br>
contain 2 integer representing the starting point and the ending point of a ladder respectively.<br>
<br>
The next line contain interger M(Number of snakes) and after that M line follow. Each of the M line contain 2<br>
integer representing the starting point and the ending point of a snake respectively.<br>
<br>
Output Format<br>
<br>
For each of the T test cases, output one integer, each in a new line, which is the least number of moves<br>
(or rolls of the die) in which the player can reach the target square (Square Number 100) after starting at the<br>
base (Square Number 1). This corresponds to the ideal sequence of faces which show up when the die is rolled.<br>
If there is no solution, print -1. <br>
<br>
Sample Input/Output:<br>
Input:<br>
2<br>
3<br>
32 62<br>
42 68<br>
12 98<br>
7<br>
95 13<br>
97 25<br>
93 37<br>
79 27<br>
75 19<br>
49 47<br>
67 17<br>
4<br>
8 52<br>
6 80<br>
26 42<br>
2 72<br>
9<br>
51 19<br>
39 11<br>
37 29<br>
81 3<br>
59 5<br>
79 23<br>
53 7<br>
43 33<br>
77 21 <br>
<br>
Output:<br>
3<br>
5<br>
<br>

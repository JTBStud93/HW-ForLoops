# HW-ForLoops
Watch read and practice from the module: For Loops, Foreach Loops. Write your understanding of the topic using comments and examples (at least 10 examples) to the instructor and describe them in your own words to the best of your knowledge. Put your work to GIT. Submit the GIT url to canvas. 

1) The integer "x" is assigned to "5". 5 is less than 10; afterwards, the incrementor increases "x" by 1. This repeats untill it reads "10 is less than 10", aka, its a false statement.

for(int x = 5; x < 10; x++)
{
  print("Value of x: {0}", x);
}

/*
Value of x: 5
Value of x: 6
Value of x: 7
Value of x: 8
Value of x: 9
*/

2) The integer "x" is assigned to "4". 4 is less than 12; afterwards, the "add & assignment" operator increases "x" by 2. This repeats untill its a false statement.

for(int x = 4; x < 12; x+=2)
{
  print(x);
}

/* Outputs
4
6
8
10
*/

3) The integer "x" is assigned to "18". 18 is greater than 7; afterwards, the "subtract & assignment" operator decreases "x" by 3. This repeats untill its a false statement.

for(int x = 18; x > 7; x-=3)
{
  print(x);
}

/* Outputs
18
15
12
9
*/

4) Optionally, the init-clause (int x = 4;)can be placed above the ForLoop expression (with a semicolon), but the (space &) semicolon must be included within the parentheses.

int x = 4;
for( ; x > 0; x-=1)
{
  print(x);
}

/* Outputs
4
3
2
1
*/

5) Similar to #4, the iteration-clause (x-=1;) can be placed below the print / Console.Writeline expression.

int x = 4;
for( ; x > 0; )
{
  print(x);
  x-=1;
}

/* Outputs
4
3
2
1
*/

6) In this example, it has a continue statement. Unlike the break statement, this will not terminate the loop once "x" or "0" is compared to "4". It will stop, however, once "x" is increased to "6", which will read false, and 6 will not be included in the output.

for(x = 0; x < 6; x++)
{
  if (x == 4);
    continue;
    
  print(x);
}

/* Outputs
0
1
2
3
5
*/

7) Similar to #6, only this time we now have a decrement operator (x--).

for(x = 19; x > 9; x--)
{
  if (x == 11);
    continue;
    
  print(x);
}

/* Outputs
19
18
17
16
15
14
13
12
10
*/

8) Similar to #2, but this time one of the math operators used here is "greater than or equal to" (<=). So once "x" becomes "25", it will be included in the output.

for(int x = 5; x <= 25; x+=5)
{
  print(x);
}

/* Outputs
5
10
15
20
25
*/

9) Similar to #8, this time with the "less than or equal to" (>=).

for(int x = 49; x >= 7; x-=7)
{
  print(x);
}

/* Outputs
49
42
35
28
21
14
7
*/

10) Based on the example shown on the Unity tutorial, we declare the number of Characters in the Debug.Log (which is 4 in this case). This loop will stop once "x" is added up to "4" (till its false). On a side note, counting begins at zero, not one.

int numCharacters = 4

void Start ()
{
  for(int x = 0; x < numCharacters; x++)
  {
    Debug.Log("Here is character number:" + x);
  }
}

/* Outputs
Here is character number 0
Here is character number 1
Here is character number 2
Here is character number 3
*/

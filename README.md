# HW-ForLoops
Watch read and practice from the module: For Loops, Foreach Loops. Write your understanding of the topic using comments and examples (at least 10 examples) to the instructor and describe them in your own words to the best of your knowledge. Put your work to GIT. Submit the GIT url to canvas. 

1)

for (int x = 5; x < 10; x++)
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

2)

for (int x = 4; x < 12; x+=2)
{
  print(x);
}

/* Outputs
4
6
8
10
*/

3)

for (int x = 18; x > 7; x-=3)
{
  print(x);
}

/* Outputs
18
15
12
9
*/

4)

int x = 4;
for ( ; x > 0; x-=1)
{
  print(x);
}

/* Outputs
4
3
2
1
*/

5)

int x = 4;
for ( ; x > 0; )
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

6)

for (x = 0; x < 6; x++)
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

7)

for (x = 19; x > 9; x--)
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

8)

for (int x = 5; x <= 25; x+=5)
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

9)

for (int x = 49; x >= 7; x-=7)
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

using UnityEngine;
using System.Collections;

public class ForLoop : MonoBehaviour
{
    int numEnemies = 3;
    
    
    void Start ()
    {
        for(int i = 0; i < numEnemies; i++)
        {
            Debug.Log("Creating enemy number: " + i);
        }
    }
}

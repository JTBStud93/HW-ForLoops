# HW-ForLoops
Watch read and practice from the module: For Loops, Foreach Loops  Write your understanding of the topic using comments and examples (at least 10 examples) to the instructor and describe them in your own words to the best of your knowledge. Put your work to GIT. Submit the GIT url to canvas. 

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

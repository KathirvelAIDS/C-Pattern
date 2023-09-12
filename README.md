# Pattern

## Aim:
To write a C# program for a pascal's triangle.



## Equipment Required:
visual studio

## Algorithm:\
```
Step 1:

Create a class.

Step 2:

Use nested for loop.

Step 3:

End the for loop
```

## Program:

```
NAME:KATHIRVEL.A
REG NO:212221230047
```


```
using System;
namespace condition
{
    public class pascal
    {
        public static void Main(string[] args)
        {
            int rows , Val = 1;
            Console.Write("Enter number of rows: ");
            rows = Convert.ToInt32(Console.ReadLine()); 
            for (int i = 0; i < rows; i++)
            {
                for (int blank = 1; blank < rows - i; blank++)
                {
                    Console.Write(" ");
                }
                for (int j = 0; j <= i; j++)
                {
                    if (i == 0 || j == 0)
                    {
                        Val = 1;
                    }
                    else
                    {
                        Val = Val * (i - j + 1) / j;
                    }
                    Console.Write(Val + " ");
                }
                Console.WriteLine();
            }
        }
    }
}

```

## Output:




![image](https://github.com/KathirvelAIDS/C-Pattern/assets/94911373/4b193574-189a-4d5f-8f52-04d74c58594f)



## Result:



Thus the C# program to print the pascal's triangle is executed successfully.


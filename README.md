# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
Step1:

Start

Step2:

Create a class and declare three variable with integer datatype

Step3:

Use if condition to check whether num1 is largest than num2 and num3

Step4:

Use elif condition to check whether num2 is largest than num1 and num3

Step5:

Use else condition to display that third variable is largest among all the variables

Step6:

stop

## Program:
```c#
using System;
namespace lg
{
    class LargeNo
    {
        static void Main(string[] args)
        {
            
            int a,b,c;
            Console.WriteLine("Enter The Values :");
            a=Convert.ToInt32(Console.ReadLine());
            b=Convert.ToInt32(Console.ReadLine());
            c=Convert.ToInt32(Console.ReadLine());

            
            if(a>b && a>c)
            {
                Console.WriteLine("a Is Greater");
            }
            else if(b>a && b>c)
            {
                Console.WriteLine("b Is Greater");
            }
            else
                Console.WriteLine("c Is Greater");
        }
    }
}
```

## Output:
![image](https://github.com/veerapallijanith/Largest-of-three-numbers/blob/main/exp%201%20jc%23.jpg)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully

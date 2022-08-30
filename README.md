# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

## Program:
```

using System;
namespace ThreeNumbers{
public class GreatestOfThree
{
    public static void Main(string[] args)
    {
         int num1, num2, num3;
                Console.WriteLine("Enter any three number : ");
                num1 = Convert.ToInt32(Console.ReadLine());
                num2 = Convert.ToInt32(Console.ReadLine());
                num3 = Convert.ToInt32(Console.ReadLine());
            if ((num1 > num2) && (num1 > num3))
                Console.WriteLine(num1 + " is the greatest");
            else if ((num2 > num1) && (num2 > num3))
                Console.WriteLine(num2 + " is the greatest");
            else
                Console.WriteLine(num3 + " is the greatest");
    }
}
}
```

## Output:

![Screenshot from 2022-08-30 17-39-47](https://user-images.githubusercontent.com/75234646/187431623-0a82ec3a-ff55-4cc3-a496-6a1c118e3c2d.png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully

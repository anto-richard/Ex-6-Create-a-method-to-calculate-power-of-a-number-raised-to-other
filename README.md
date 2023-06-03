# Ex-6-Create-a-method-to-calculate-power-of-a-number-raised-to-other...

## AIM:

To write a java program to create a method to calculate power of a number raised to other.

## ALGORITHM:

### Step 1:

Import the necessary packages.

### Step 2:

Get the base and power values from the user.

### Step 3:

Using recursive function, calculate the power value.

### Step 4:

Print the result.

### Step 5:

End the program.

## PROGRAM:

```java

Name   : Anto Richard. S
Reg No : 212221240005

import java.util.*; 
public class Power 
{ 
    public static void main(String[] args) 
    { 
        Scanner s = new Scanner(System.in); 
        System.out.print("Enter the value of ’a’ : "); 
        int a = s.nextInt(); 
        System.out.print("Enter the value of ’b’ : "); 
        int b = s.nextInt(); 
        int res = pow(a,b); 
        System.out.println(a + " raised to the power of " + b + " is " + res); 
    } 
    public static int pow(int a, int b) 
    { 
        if (b == 0) 
        { 
            return 1; 
        } 
        else if (b % 2 == 0) 
        { 
            int half = pow(a,b / 2); 
            return half * half; 
        } 
        else 
        { 
            return a * pow(a,b- 1); 
        } 
    } 
}

```

## OUTPUT:

![g2](https://github.com/anto-richard/Ex-6-Create-a-method-to-calculate-power-of-a-number-raised-to-other/assets/93427534/942805cc-0fa3-4a60-9063-b548d85858f1)

## RESULT:

Thus the java program to create a method to calculate power of a number raised to other is executted successfully.

# Exp-6-java
## Aim:
To code a program that produces output of power value for the corresponding base and exponnent.
## Algorithm:
### Step1:
Import the required packages.
### Step2:
Using for loop find thr respective power.
### Step3:
With respect to the user input display the result.
## Code:
```
import java.util.Scanner;
public class Exp6 {
         static int power(int base, int exponent)
        {
            int power = 1;
             for (int i = 1; i <= exponent; i++)
                 power = power * base;
             return power;
        }
        public static void main(String args[])
        {
            int base, exponent;
            Scanner sc=new Scanner(System.in);
            System.out.print("Enter the base: ");
            base=sc.nextInt();
            System.out.print("Enter the exponent: ");
            exponent=sc.nextInt();

            int pow=power(base, exponent);
             System.out.println(base +" to the power " +exponent + " is: "+pow);
        }
    }


```
## Output:
![image](https://github.com/Archana2003-Jkumar/Exp-6-java/assets/93427594/a86348f2-17f1-4c90-a9b8-709561dab624)
## Result:
Hence the program has been successfully executed.

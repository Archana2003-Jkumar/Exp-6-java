# Exp-6-java
## Aim:
To code a program that fins the number of day in a month.
## Algorithm:
### Step1:
Import the required packages.
### Step2:
Using switch statement for each case give the respective days.
### Step3:
Respect to the user input display the result.
## Code:
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        System.out.println("Enter the month number: ");
        int month=input.nextInt();
        switch(month)
        {
            case 1:
                System.out.println("31 days");
                break;
            case 2:
                System.out.println("28 days");
                break;
            case 3:
                System.out.println("31 days");
                break;
            case 4:
                System.out.println("30 days");
                break;
            case 5:
                System.out.println("31 days");
                break;
            case 6:
                System.out.println("30 days");
                break;
            case 7:
                System.out.println("31 days");
                break;
            case 8:
                System.out.println("31 days");
                break;
            case 9:
                System.out.println("30 days");
                break;
            case 10:
                System.out.println("31 days");
                break;
            case 11:
                System.out.println("30 days");
                break;
            case 12:
                System.out.println("31 days");
                break;
            default:
                System.out.println("Enter appropriate month");
        }
    }
}
```
## Output:
![image](https://github.com/Archana2003-Jkumar/Exp3-java/assets/93427594/c24699ba-2c51-4436-8f53-b26167a3c280)
## Result:
Hence the program has been successfully executed.

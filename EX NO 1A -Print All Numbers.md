# EX 1A Print All Numbers 
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm
1.Start the program.

2.Input an integer N from the user.

3.Check condition: If N <= 0, display "Invalid input. N must be greater than 0." and stop.

4.Initialize a variable i = 1.

5.Use a loop to print numbers from 1 to N:

While i <= N, print i followed by a space.

Increment i by 1.

End loop and stop the program.

## Program:


Program to implement Reverse a String
## Developed by:  SHARON CLARA A
## Register Number:  212224040310

```


import java.util.*; 
public class demo   
{
    public static void main(String args[]) 
    {
        int N,i;
        Scanner sc=new Scanner(System.in);
        N=sc.nextInt();  
        if(N<=0)
        {
            System.out.println("Invalid input. N must be greater than 0.");
            
        }
        else{
            for(i=1;i<=N;i++){
                System.out.print(i+" ");    
            }
        }
    }
}

```

## Output:

<img width="421" height="149" alt="647067805-61fb5635-e6b5-437f-aeeb-b058798cb5b5" src="https://github.com/user-attachments/assets/506bd5a2-168a-4f0e-a361-319c750bbbd1" />





## Result:
The program successfully print all the numbers from 1 to N. 

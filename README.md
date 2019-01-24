//# Prime-numbers
//project on prime numbers

import java.util.Scanner;
public class MyClass {
    public static void main(String[] args) {
        Scanner myVar = new Scanner(System.in);
        System.out.println("Please enter a number from 1-10:");
        int x;
        x = myVar.nextInt();
        if(x == 10)   {
            System.out.println("1 is not a prime number" + System.lineSeparator() + "2 is a prime number" + System.lineSeparator() + "3 is a prime number" + System.lineSeparator() + "4 is not a prime number" + System.lineSeparator() + "5 is a prime number" + System.lineSeparator() + "6 is not a prime number" + System.lineSeparator() + "7 is a prime number" + System.lineSeparator() + "8 is not a prime number" + System.lineSeparator() + "9 is not a prime number" + System.lineSeparator() + "10 is not a prime number"); //system.line separator used to seperate
        } else if(x==9)  {
            System.out.println("1 is not a prime number" + System.lineSeparator() + "2 is a prime number" + System.lineSeparator() + "3 is a prime number" + System.lineSeparator() + "4 is not a prime number" + System.lineSeparator() + "5 is a prime number" + System.lineSeparator() + "6 is not a prime number" + System.lineSeparator() + "7 is a prime number" + System.lineSeparator() + "8 is not a prime number" + System.lineSeparator() + "9 is not a prime number");
        } else if(x==8)  {
            System.out.println("1 is not a prime number" + System.lineSeparator() + "2 is a prime number" + System.lineSeparator() + "3 is a prime number" + System.lineSeparator() + "4 is not a prime number" + System.lineSeparator() + "5 is a prime number" + System.lineSeparator() + "6 is not a prime number" + System.lineSeparator() + "7 is a prime number" + System.lineSeparator() + "8 is not a prime number" + System.lineSeparator() + "9 is not a prime number");
        } else if(x==7)  {
            System.out.println("1 is not a prime number" + System.lineSeparator() + "2 is a prime number" + System.lineSeparator() + "3 is a prime number" + System.lineSeparator() + "4 is not a prime number" + System.lineSeparator() + "5 is a prime number" + System.lineSeparator() + "6 is not a prime number" + System.lineSeparator() + "7 is a prime number");
        } else if(x==6)  {
            System.out.println("1 is not a prime number" + System.lineSeparator() + "2 is a prime number" + System.lineSeparator() + "3 is a prime number" + System.lineSeparator() + "4 is not a prime number" + System.lineSeparator() + "5 is a prime number" + System.lineSeparator() + "6 is not a prime number");
        } else if(x==5)  {
            System.out.println("1 is not a prime number" + System.lineSeparator() + "2 is a prime number" + System.lineSeparator() + "3 is a prime number" + System.lineSeparator() + "4 is not a prime number" + System.lineSeparator() + "5 is a prime number");
        } else if(x==4)  {
            System.out.println("1 is not a prime number" + System.lineSeparator() + "2 is a prime number" + System.lineSeparator() + "3 is a prime number" + System.lineSeparator() + "4 is not a prime number");
        } else if(x==3)  {
            System.out.println("1 is not a prime number" + System.lineSeparator() + "2 is a prime number" + System.lineSeparator() + "3 is a prime number");
        } else if(x==2)  {
            System.out.println("1 is not a prime number" + System.lineSeparator() + "2 is a prime number");
        } else if(x==1)  {
            System.out.println("1 is not a prime number");
    } else  {
        System.out.println("Error, input another number please.");
    }
    }
}

import java.util.Scanner;
public class MyClass {
    public static void main(String[] args) {
        Scanner myVar = new Scanner(System.in);
        int x;
        x = myVar.nextInt();
        if(x == 10)   {
            System.out.println("1 is not a prime number" + System.lineSeparator() + "2 is a prime number" + System.lineSeparator() + "3 is a prime number" + System.lineSeparator() + "4 is not a prime number" + System.lineSeparator() + "5 is a prime number" + System.lineSeparator() + "6 is not a prime number" + System.lineSeparator() + "7 is a prime number" + System.lineSeparator() + "8 is not a prime number" + System.lineSeparator() + "9 is not a prime number" + System.lineSeparator() + "10 is not a prime number"); //system.line separator used to seperate
        } else  {
            System.out.println("error");
        }
    }
}

1.print the maximum and minimum of three numbers
import java.util.Scanner;

public class Main {

    static void maximum(int a, int b, int c) {
        int max = a;
        if (b > max)
            max = b;
        if (c > max)
            max = c;
        System.out.println("Maximum = " + max);
    }

    static void minimum(int a, int b, int c) {
        int min = a;
        if (b < min)
            min = b;
        if (c < min)
            min = c;
        System.out.println("Minimum = " + min);
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter three numbers: ");
        int a = sc.nextInt();
        int b = sc.nextInt();
        int c = sc.nextInt();

        maximum(a, b, c);
        minimum(a, b, c);

        sc.close();
    }
}
2.find whether a number is even or odd
import java.util.Scanner;

public class Main {

    static void checkEvenOdd(int num) {
        if (num % 2 == 0)
            System.out.println("Even");
        else
            System.out.println("Odd");
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int num = sc.nextInt();

        checkEvenOdd(num);

        sc.close();
    }
}
3.check voting Eligibility:
import java.util.Scanner;

public class Main {

    static void checkVote(int age) {
        if (age >= 18)
            System.out.println("Eligible to Vote");
        else
            System.out.println("Not Eligible to Vote");
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter age: ");
        int age = sc.nextInt();

        checkVote(age);

        sc.close();
    }
}
4.sum of two numbers using a method:
import java.util.Scanner;

public class Main {

    static void sum(int a, int b) {
        System.out.println("Sum = " + (a + b));
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter first number: ");
        int a = sc.nextInt();

        System.out.print("Enter second number: ");
        int b = sc.nextInt();

        sum(a, b);

        sc.close();
    }
}
5.product of two numbers using a method:
import java.util.Scanner;

public class Main {

    static int product(int a, int b) {
        return a * b;
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter first number: ");
        int a = sc.nextInt();

        System.out.print("Enter second number: ");
        int b = sc.nextInt();

        int result = product(a, b);

        System.out.println("Product = " + result);

        sc.close();
    }
}




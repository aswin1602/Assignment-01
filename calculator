import java.util.*;
public class ConsoleCalci {
    static int add(int a, int b) {
        return a + b;
    }
    static int subtract(int a, int b) {
        return a - b;
    }
    static int multiply(int a, int b) {
        return a * b;
    }
    static double divide(int a, int b) {
        if (b == 0) {
            System.out.println("Error!");
            return 0;
        }
        return (double) a / b;
    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        while (true) {
            System.out.println("--- Simple Calculator ---");
            System.out.println("1. Add");
            System.out.println("2. Subtract");
            System.out.println("3. Multiply");
            System.out.println("4. Divide");
            System.out.println("5. Exit");
            System.out.print("Choose an option (1-5): ");
            int choice = sc.nextInt();
            if (choice == 5) {
                System.out.println();
                break;
            }
            System.out.print("Enter first number: ");
            int num1 = sc.nextInt();
            System.out.print("Enter second number: ");
            int num2 = sc.nextInt();
            if (choice == 4) {
                double result = divide(num1, num2);
                System.out.println("Result: " + result);
            } else {
                int result = 0;
                switch (choice) {
                    case 1:
                        result = add(num1, num2);
                        System.out.println("Result: " + result);
                        break;
                    case 2:
                        result = subtract(num1, num2);
                        System.out.println("Result: " + result);
                        break;
                    case 3:
                        result = multiply(num1, num2);
                        System.out.println("Result: " + result);
                        break;
                    default:
                        System.out.println("Invalid option.");
                        break;
                }
            }
        }
        System.out.println("Exiting the calculator...!");
    }
}

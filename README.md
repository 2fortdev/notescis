import java.util.Scanner;

public class AddMethod {

    public static void main(String args[]) {
    
        int num1;
        int num2;
        Scanner scan = new Scanner(System.in);
        
        System.out.println("please enter number one and number 2");
        
        num1 = scan.nextInt();
        num2 = scan.nextInt();
        
        
        int result = addNumbers(num1,num2);
        int result1 = subNumbers(num1,num2);
        int result2 = multiNumbers(num1,num2);
        
        displayTopic();
        System.out.println("Sum is " + result);
        System.out.println("Difference is " + result1);
        System.out.println("Product is " + result2);
    }
    
    public static int addNumbers(int a, int b){
        int sum = a + b;
        return sum;
        
    }
    
    public static int subNumbers(int a, int b){
        int sub = a - b;
        return sub;
        
    }
    public static int multiNumbers(int a, int b){
        int mult = a * b;
        return mult;
        
    }
    
    public static void displayTopic() {
        System.out.println("Addition of two numbers ");
        System.out.println("----------------------- ");
        
        
    }
    
}

import java.util.Scanner;
public class oddEven {
    public static void main(String[] args) {
        Scanner in = new Scanner (System.in);
        System.out.println("Enter a random Number ");
        int inp = in.nextInt();
        if (inp%2==0){
            System.out.println("This is a Even Number Dude");
        }
        else {
            System.out.println("You entered a odd number ");
        }
    }
    
}

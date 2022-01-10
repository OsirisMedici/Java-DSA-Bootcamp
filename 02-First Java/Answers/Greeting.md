import java.util.Scanner;
public class greeting {
    public static void main(String[] args) {
        System.out.println("What's your name Buddy: ");
        Scanner in = new Scanner(System.in);
        String greet = in.next();
        System.out.println("You have a very good day today "+ greet);
        
    }
}

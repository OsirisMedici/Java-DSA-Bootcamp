import java.util.Scanner;
public class Rhombus {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        System.out.println("Enter size of first diagonal: ");
        float a = in.nextFloat();
        System.out.println("Enter size of Second diagonal: ");
        float b = in.nextFloat();
        float area = ((a*b)/2);
        System.out.println("let's print the area of your rhombus: ");
        System.out.println(area);
    } 
}

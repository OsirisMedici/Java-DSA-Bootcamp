import java.util.Scanner;
public class EquilateralTriangle {
    public static void main(String[] args) {
        Scanner in = new Scanner (System.in);
        System.out.println("Enter the size of the side of your traingle: ");
        float a = in.nextFloat();
        float area = (a*a*a);
        System.out.println("Let's find out the area " + area);
    }
}

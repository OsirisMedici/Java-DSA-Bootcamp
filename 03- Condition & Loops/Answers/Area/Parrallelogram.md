import java.util.Scanner;
public class parallegram {
    public static void main(String[] args) {
        Scanner in = new Scanner (System.in);
        System.out.println("Enter the size of first side: ");
        float a = in.nextFloat();
        System.out.println("Enter the size of Second side: ");
        float b = in.nextFloat();
        System.out.println("Enter the size of first side: ");
        double angle = Math.toRadians(in.nextFloat());
        double area = a*b*Math.sin(angle);
        System.out.println("Your area " + area);
    }
}

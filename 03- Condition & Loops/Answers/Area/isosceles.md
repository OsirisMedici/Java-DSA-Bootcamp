import java.util.Scanner;
public class Isosceles {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.println("Enter the size of the equal side of triangle: ");
        float a = s.nextFloat();
        System.out.println("Enter the size of the other side of triangle: ");
        float b = s.nextFloat();
        double area = a * Math.sqrt((b*b)-((a*a)/4)) / 2;
        System.out.println("The area of this structure12");
        System.out.println(area);

    }
}

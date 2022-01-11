import java.util.Scanner;
public class circle {
    public static void main(String[] args) {
        System.out.println("give us the radius: ");
        Scanner in = new Scanner(System.in);
        
        int r = in.nextInt();
        
        float pi =  3.14f;
        
        float area = (pi*r*r);
        
        System.out.println("So the area of this circle will be: ");
        
        System.out.println(area); 

    }
}

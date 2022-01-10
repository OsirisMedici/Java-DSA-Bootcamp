import java.util.Scanner;
public class interest {
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        System.out.println("Enter initial amount ");
        int p = in.nextInt();
        System.out.println("how much time in years ");
        int t = in.nextInt();
        System.out.println("rate in percent ");
        float r = in.nextFloat();

        float a =  ((p*r*t)/100);
        System.out.println("Simple intrest of this will be some; ");
        System.out.println(a);

        System.out.println("You have to return total; ");
        float ret = (a+p);
        System.out.println(ret);
    }
    
}

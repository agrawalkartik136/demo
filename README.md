# demo
 1
import java.util.Scanner;
public class expression2
{
    public static void main(String args[])
    {
        Scanner in=new Scanner(System.in);
        double a=5,b=4,c=3,res=0;
        res=(a*a+b*b+c*c)/(a*b*c);
        System.out.println("The result is:"+res);
    }
}
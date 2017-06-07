import java.io.*;
import java.util.*;
public class ras
{
public static void main(String args[])
{
 Scanner s=new Scanner(System.in);
 int a=s.nextInt();
 if(a<0)
 {
 System.out.println("neg");
 }
 else if(a==0)
 {
 System.out.println("zero");
 }
 else
 {
 System.out.println("pos");
 }
}
}

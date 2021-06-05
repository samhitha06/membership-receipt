# membership-receipt 
import java.util.*;
class Prime
{
Scanner sc=new Scanner(System.in);
double charge;
public void get()
{
System.out.println("enter the name of the costumer");
String n=sc.next();
System.out.println("enter the number of months");
int months=sc.nextInt();
if(months<=3)
charge=months*1500;
else if(months<=6)
charge=(3*1500)+(months-3)*1450;
else if(months<=10)
charge=(3*1500)+(3*1450)+(months-6)*1300;
else if(months>10)
charge=(3*1500)+(3*1450)+(4*1400)+(months-10)*1300;
else
System.out.println("wrong input");
System.out.println("the costumer name is" +n);
System.out.println("number of months are " +months);
System.out.println("the charge is " +charge);
}
}

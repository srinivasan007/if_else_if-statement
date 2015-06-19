# if_else_if-statement
import java.util.Scanner;
class if_else_if
{
public static void main(String agrs[])
{
Scanner s=new Scanner(System.in);
System.out.println("enter the a value:");
int a=s.nextInt();
System.out.println("enter the b value:");
int b=s.nextInt();
System.out.println("enter the c value:");
int c=s.nextInt();
int total=a+b+c;
int ave=total/3;
	if(ave>=90)
	{
	System.out.println("s grade");
	}
	else if(ave>=80)
	{
	System.out.println("a  grade");
	}
	else if(ave>=70)
	{
	System.out.println("b grade");
	}
	else if(ave>=60)
	{
	System.out.println("c grade");
	}
	else if(ave>=50)
	{
	System.out.println("e grade");
	}
	else{
	System.out.println("fail");
	}
}
}

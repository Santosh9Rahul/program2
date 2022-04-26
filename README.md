package aaa;
import java.util.Scanner;

public class bbb {

	public static void main(String[] args) {
	
		Scanner scan=new Scanner(System.in);
		System.out.println("enter a value of A");
		double a=scan.nextDouble();
		a=a+(a-1);
		for(int i=0;i<=a;i++)
		{
			
			if(i%2==1)
			{
			System.out.println(i);
			}
			
			
		}
	}

}

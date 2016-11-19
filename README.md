# ACD_JAVAB2_Session_2_Assignment_4
package _Main;
import java.util.Scanner;

public class ACD_JAVAB2_Session_2_Assignment_4 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
    
		int m1,m2,m3;
		Scanner sc = new Scanner(System.in);
		System.out.println("enter the first number:");		
		m1=sc.nextInt();
		System.out.println("enter the second number:");		
		m2=sc.nextInt();
		System.out.println("enter the third number:");		
		m3=sc.nextInt();
		if (m1>m2 && m1>m3){
			System.out.println("First number is the greatest one:" + m1);			
		}
		else if (m2>m3){
			System.out.println("second number is the greatest one:" + m2);
		}
		else 
		{
			System.out.println("third number is the greatest one:" + m3);
		}
		
		}
		
}

Solstice
================
import java.util.*;
public class Part1 {
//GOAL: finish by Friday
  public static void main(String[] args) {

	System.out.println("You wake up in a room. You don\"t know where you are.");
	System.out.println("There is a door. There is a combination lock on it.");
	System.out.println(" Behind you there four math problems, maybe they can help.");
	RoomOne();
	
	
	//-----------------------------------ROOM ONE---------------------------------------
	} static void RoomOne() 
	{
		Scanner scanner=new Scanner(System.in);
		int A, B, C, D, sum, a, b, c, d;
		
			
		
		System.out.println("The first problem reads: 4+3 What is the answer?");
		A=scanner.nextInt();
		System.out.println("Take note of that...you might need it soon.");
		System.out.println("Ok, the second problem is 16-8");
		B=scanner.nextInt();
		System.out.println("Two down, two to go!");
		System.out.println("The next one reads: 2x3 this is a tough one.");
		C=scanner.nextInt();
		System.out.println("You are almost done, this is the last one.");
		System.out.println("72/8 uh oh, too bad you don\"t have a calculator!");
		D=scanner.nextInt();
		System.out.println("You have your answers, you go to the door.");
		System.out.println("(you enter you numbers)");
		sum= (A+B+C+D);
		while (sum > 30||sum<30)
		{
			sum = 0;
			System.out.println("You did something wrong, Try again");
			System.out.println("4+3");
			a=scanner.nextInt();
			System.out.println("16-8");
			b=scanner.nextInt();
			System.out.println("2x3");
			c=scanner.nextInt();
			System.out.println("72/8");
			d=scanner.nextInt();
			sum=(a+b+c+d);
		}
	}
The-Evil-Program
================

import java.util.*;
public class GuiReview2 {
//GOAL: finish by Friday
  public static void main(String[] args) {

	System.out.println("You wake up in a room. You don\"t know where you are.");
	System.out.println("There is a door. There is a combination lock on it.");
	System.out.println(" Behind you there four math problems, maybe they can help.");
	//RoomOne();
	//RoomTwo();
	RoomThree();
	
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
	
//--------------------------------------ROOM TWO-------------------------------------
	static void RoomTwo() {
		Scanner scanner=new Scanner(System.in);
		System.out.println("You open the door and walk in.");
		System.out.println("You are in another room. There is another locked door.");
		System.out.println("This lock is different. It uses letters. It could be anything! You look for clues.");
		System.out.println("On the floor there is a paper. You pick it up. It reads:");
		System.out.println("I never expire, I am sweet and thick");
		System.out.println("You think of three things:");
		int E; 
		do
		 {
			 System.out.println("1.Butter");
			 System.out.println("2.Honey");
			 System.out.println("3.Molasses");
			 System.out.println("(say \"1\" if you think Butter, etc)");
			 E=scanner.nextInt();
		 } while (E>2||E<2);
		System.out.println("That did it!");
	}
//--------------------------------------ROOM THREE------------------------------------
	static void RoomThree() 
	{
		Scanner scanner=new Scanner(System.in);
		Random random= new Random();
		System.out.println("The light stings your eyes as you walk through the door, your outside.");
		System.out.println("There is a house to your left and to your right.");
		System.out.println("After liitle consideration, you go to the right one, for the left one was a dump!");
		System.out.println("You twist the handle and realize it\"s locked");
		System.out.println("\"Friend or foe?!\" A voice yells.");
		System.out.println("\"uhh...Friend?\"");
		System.out.println("\"oh\" The man unlocked the door \"can\"t really trust anyone anymore.\"");
		System.out.println("\"why?\"");
		System.out.println("\"Is that a joke? Don\"t you know where you are?\"");
		System.out.println("\"No, I was just in that room--\"");
		System.out.println("\"That\"s how it starts for everyone. We are lab rats, people are watching, oh...they are allways watching.\"");
		System.out.println("\"What do you mean? I-I don\"t understand\" You are confused.");
		System.out.println("\"We are being tested. We ARE the test. All around us is wasteland. As far as I know, It\"s only you and me.\"");
		System.out.println("\"What do we have to worry about?\"");
		System.out.println("\"Everything. This world...it\"s not real, we are inside a program. A BAD program. They can send virtually anything at us\"");
		System.out.println("\"Your lying! I\"m out of here!\" You turn and run out the door. You run into something. You look up, you\"re not sure what it is.");
		System.out.println("\"You can\"t run from it!\" Shouted the man. \"You have to fight it\" he tossed you a cane.");
		System.out.println("(When the monster attacks right, type l to dodge. If it attacks left. type r.)");
		char chara;
		int F;
		F=random.nextInt(1);
		//-----------------------Still a work in progress----------------------------------
		
	}
	
	
	
		}
	



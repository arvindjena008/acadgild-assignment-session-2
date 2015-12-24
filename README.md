# acadgild-assignment-session-2
assignment for session 2
 
 Assignment-1
 import java.util.Scanner;

public class AgeVote {

	public static void main(String[] args) {
		int age;
		System.out.print("Enter your age: ");
		Scanner in = new Scanner(System.in); 
		age = in.nextInt();
		if(age>=1&&age<=100)
		{
			if(age>=18)
			{
				System.out.println("You are eligible for vote...........");
				return;
			}	
			System.out.println("You are not eligible for vote..........");
			return;
		}
			System.out.println("Invalid Age........please try again!!!!");

	}

}

Assignment-2
import java.util.Scanner;

public class PrimeNum {

	public static void main(String[] args) {
		 		
		      Scanner in = new Scanner(System.in);
		      int i,num,counter;
		      String  primeNumbers = "";
		      System.out.println("Enter the value of n:");
		      int n = in.nextInt();
		      for (i = 1; i <= n; i++)  	   
		      { 		 		  
		         counter=0; 		  
		         for(num =i; num>=1; num--)
		         {
		        	 if(i%num==0)
		        	 {
		        		 counter = counter + 1;
		        	 }
		         }
		         if (counter ==2)
		         {
			        primeNumbers = primeNumbers + i + " ";
		         }	
		      }	
		      System.out.println("Prime numbers from 1 to "+n+" are :");
		      System.out.println(primeNumbers);
		   
	}

}

Assignment-3

public class PatternPyramidNum {

	public static void main(String[] args) {
		int i,j,k;
		for(i=1;i<=5;i++)
		{
			for(j=1;j<=i;j++)
			 System.out.print(j);
			System.out.println();
		}
		for(i=1,k=5;i<=5;i++,k--)
		{
			for(j=1;j<k;j++)
			 System.out.print(j);
			System.out.println();
		}

	}

}

Assignment-4
import java.util.Scanner;

public class DayInMon {

	public static void main(String[] args) {
		int month;
		System.out.print("Enter the month number: ");
		Scanner in = new Scanner(System.in);
		month = in.nextInt();
		switch(month)
		{
		case 1:System.out.println("No.of days in January is 31");break;
		case 2:System.out.println("No.of days in February is 28");break;
		case 3:System.out.println("No.of days in March is 31");break;
		case 4:System.out.println("No.of days in April is 30");break;
		case 5:System.out.println("No.of days in May is 31");break;
		case 6:System.out.println("No.of days in June is 30");break;
		case 7:System.out.println("No.of days in July is 31");break;
		case 8:System.out.println("No.of days in August is 31");break;
		case 9:System.out.println("No.of days in September is 30");break;
		case 10:System.out.println("No.of days in October is 31");break;
		case 11:System.out.println("No.of days in November is 30");break;
		case 12:System.out.println("No.of days in December is 31");break;
		default:System.out.println("Invalid Month!!!!!!!!!!!!");
		}

	}

}

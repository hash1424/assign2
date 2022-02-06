# assign2
q1)import java.util.Scanner;
public class product {

	public static void main(String[] args) 
		{
		  Scanner in = new Scanner(System.in);
		  
		   
		  System.out.println(" first number: ");
		  int num1 = in.nextInt();
		   
		  System.out.println("second number: ");
		  int num2 = in.nextInt();
		   
		  System.out.println(num1 + " x " + num2 + " = " + num1 * num2);
		 
		 
		}
}
q2)import java.util.Scanner;
public class product {

	public static void main(String[] args) 
		{
		  Scanner in = new Scanner(System.in);
		  
		   
		  System.out.println(" first number: ");
		  int num1 = in.nextInt();
		   
		  System.out.println("second number: ");
		  int num2 = in.nextInt();
		   
		  System.out.println(num1 + " x " + num2 + " = " + num1 * num2);
		 
		 
		}
}
q4)
import java.util.Scanner;
public class temp
{
	    public static void main(String[] args) {
	        float temp;
	        Scanner X=new Scanner(System.in);
	        System.out.println("enter the temperature in fahrenheit: ");
	        temp= X.nextFloat();
	        temp=((temp-32)*5)/9;
	        System.out.println("Temperature in celsius is: "+temp);
	    }
      
      q5)import java.util.*;
public class convertion {

		public static void main(String[] args) 
		{
			Scanner s=new Scanner(System.in);
			int a;
			a=s.nextInt();
			double c=a*0.0254;
			System.out.print(c);
	}
	}



q6)
import java.util.Scanner;
public class convertion2 
{

	    public static void main(String[] Strings) {


	        double minutesInYear = 60 * 24 * 365;

	        Scanner input = new Scanner(System.in);

	        System.out.print("Input the number of minutes: ");

	        double min = input.nextDouble();

	        long years = (long) (min / minutesInYear);
	        int days = (int) (min / 60 / 24) % 365;

	        System.out.println((int) min + " minutes is approximately " + years + " years and " + days + " days");
	    }
	}
  q7)import java.util.*;
public class palindrome { 
	   public static void main(String args[])  
	   {  
	      String original, reverse = "";   
	      Scanner in = new Scanner(System.in);   
	      System.out.println("Enter a string");  
	      original = in.nextLine();   
	      int length = original.length();   
	      for ( int i = length - 1; i >= 0; i-- )  
	         reverse = reverse + original.charAt(i);  
	      if (original.equals(reverse))  
	         System.out.println("Entered string/number is a palindrome.");  
	      else  
	         System.out.println("Entered string/number isn't a palindrome.");   
	   }  
	}  
  q9)
  import java.util.Scanner;
public class digit 
{
	   public static void main(String args[]){
	      Scanner sc = new Scanner(System.in);
	      int count = 0;
	      System.out.println("Enter a number :");
	      int num = sc.nextInt();
	      while(num!=0){
	         num = num/10;
	         count++;
	      }
	      System.out.println("Number of digits in the entered integer are : "+count);
	   }

}
q10)import java.util.Scanner;
public class evenoddd {
	public static void main (String args[]){
	Scanner scan=new Scanner(System.in);
	System.out.print("Enter the number to check odd or even: ");
	int num=scan.nextInt();
	find_Oddeven(num);
	}
	static void find_Oddeven(int num){
	if(num%2==0) 
	    System.out.println(num+" is even"); 
	else 
	    System.out.println(num+" is odd");
	}

}
q11)
import java.util.Scanner;
public class fact1 {

	public static void main(String[] args) {
		int fact=1;
		int m;
		do {
			Scanner sc= new Scanner (System.in);
			System.out.println("Enter a Number :");
			int n=sc.nextInt();

			for(int i=1;i<=n;i++) {

			fact=fact*i;
			}
			System.out.println("The factorial is "+fact);

			System.out.println("If you want run again press 1 otherwise 0");
			m=sc.nextInt();
		}while(m==1); 

	}

}
q12)278
q13)public class greaterlesser 
	{
	public static void main(String args[])
	{
	    // variable declaration
	    int num1 = 5, num2 = 10, max;
	     
	    // Largest among n1 and n2
	    max = (num1 > num2) ? num1 : num2;
	     
	    // Print the largest number
	    System.out.println("Largest number between " + num1 +
	                  " and " + num2 + " is " + max + ". " );
	}
	}


q14)public class month 
{
	    public static void main(String[] args) {

	        int month = 12;
	        String monthString;
	        switch (month) {
	            case 1:  monthString = "January";
	                     break;
	            case 2:  monthString = "February";
	                     break;
	            case 3:  monthString = "March";
	                     break;
	            case 4:  monthString = "April";
	                     break;
	            case 5:  monthString = "May";
	                     break;
	            case 6:  monthString = "June";
	                     break;
	            case 7:  monthString = "July";
	                     break;
	            case 8:  monthString = "August";
	                     break;
	            case 9:  monthString = "September";
	                     break;
	            case 10: monthString = "October";
	                     break;
	            case 11: monthString = "November";
	                     break;
	            case 12: monthString = "December";
	                     break;
	            default: monthString = "Invalid month";
	                     break;
	        }
	        System.out.println(monthString);
	    }
	}

q15)import java.io.*; 
public class wovel {
	 
	    
	    static void vowelOrConsonant(char x)
	    {
	        if (x =='a' || x =='e' || x =='i' ||
	                          x =='o' || x =='u')
	            System.out.println("Vowel");
	        else
	            System.out.println("Consonant");
	    }
q16)public class operators {
	public static void main(String[] args){
	    int x = 5;
	    int y = 7;
	    System.out.println("Area is "+(5*7)+"\nPerimeter is "+(2*(5+7)));
	  }
	}
	
  q17)ans:-20
  q18)
  public class operators {
	 public static void main(String[] args){
		    System.out.println(23 == 45);
		  }
		}
    q19)public class operators {
	public static void main(String[] args){
	    System.out.println(Math.pow(7,5));
	  }
	}
  q20)
  public class operators {
	public static void main(String[] args){
	    int a = 55;
	    int b = 70;
	    System.out.println(a < 50 && a < b);
	  }
	}
  q21)public class operators {
	 public static void main(String[] args){
		    int n, first, second, third, forth, fifth, sum;
		    n = 23462;
		   
		    first = n/10000;     
		    n = n%10000;
			
		    second = n/1000;    
		    n = n%1000;
			
		    third = n/100;       
		    n = n%100;
			
		    forth = n/10;        
		    fifth = n%10;        
			
		    sum = first + forth;
		    System.out.println("sum : "+sum);
		  }
      q22)public class reverse {

		  public static void main(String[] args) {
		    
		    int num = 1234567, reversed = 0;

		    while( num != 10)
		    {
		      int digit = num % 10;
		      reversed = reversed * 10 + digit;
		    }

		    System.out.println("Reversed Number: " + reversed);
		  }
      q23)import java.util.Scanner;
public class check  {
	    public static void main(String[] args) {
	        Scanner sc = new Scanner(System.in);
	        int num = sc.nextInt();
	        String msg = (num==10)?"yes 10":(num==20?"yes 20":(num==30?"yes 30":(num==40?"yes 40":(num==50?"yes 50":"no"))));
	        System.out.println(msg);
	}
	}




  
      

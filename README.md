hii



// Question-practice
Here I am practice coding question//
         
          
//start..//
         
// Find factors of a number//

import java.util.Scanner;
public class Main {
	
public static void  fact(int a){
	      for(int i=1;i<=a;i++){
 if(a%i == 0){
    System. out. print(i +" ");}}
          	}
	
public static void main(String[] args) {
		
Scanner sc =new Scanner(System.in);

System. out. println ("Enter Your Number");
		int num = sc.nextInt();
		System. out. println ("Factors of "+ num+ " is = ");
		fact(num);
			}
}

// Question 2 //

// Find sum of all factors of a number

import java.util.Scanner;
public class Main {
	
public static void  fact(int a){
	      int sum =0;
	      for(int i=1;i<a;i++){
		    if(a%i == 0){
          System. out. println(i +" ");
          sum=sum+i;
            }}
          System. out. println ("sum of all factors is = "+sum);
          	}
	
public static void main(String[] args) {
		
Scanner sc =new Scanner(System.in);

System. out. println ("Enter Your Number");
		int num = sc.nextInt();
		System. out. println ("Factors of "+ num+ " is = ");
		fact(num);
			}
}

// Question 3 //


// Find factors of a number

import java.util.Scanner;
public class Main {
	
public static void  fact(int a){
	  int sum =0;
	for(int i=1;i<a;i++){
		    if(a%i == 0){
          System. out. print(i +" ");
          
 System. out. println("");
          sum=sum+i;
            }}
          System. out. println ("sum of all factors is = "+sum);
          
 if(sum==a) {
          System. out. println (a +" = "+sum +" yes it is a perfect number");
          
  }
 else{
          System. out. println ("It is not a perfect number");}
          
          
}
	
public static void main(String[] args) {
		
Scanner sc =new Scanner(System.in);

System. out. println ("Enter Your Number");
		int num = sc.nextInt();
		System. out. println ("Factors of "+ num+ " is = ");
		fact(num);
			}
}


//   Question 4 //

//Leap year checker//

import java. util. *;
public class Main {
	public static void main(String[] args) {
	Scanner sc =new Scanner(System.in);
	
System. out. println ("Enter year : ");	
int year= sc. nextInt();
	if  ((year % 4 == 0) && (year % 100 != 0) || (year % 400 == 0)){
		System. out. println (year+" is a leap year");}
  else{
		    
System. out. println (year+" is not a leap year");}
		    
}
}
//Question 5//

// x number finder //
import java .util.Scanner;
public class Main
{
	public static void main(String[] args) {



Scanner sc=new Scanner (System.in);
System.out.println("Enter your number : ");

int num=sc.nextInt();

while (num>9) {

int sum = 0;

while (num != 0) {

sum = sum + num % 10;

num = num / 10;

} num= sum;}

System.out.println("Sum of all digits of given number is : " + num);

if (num == 1) {

System.out.println("Given number is a X number.");

}

else {

System.out.println("Given number is not a X number.");}

}}




// Question 6 //



import java. util. *;

public class Main {
	
public static int check(int n){
	    	int sum=0;
	while(n!=0){
	int rem=n%10;
	sum=rem+sum;
    n=n/10;
		
		}		
System. out. println ("sum = "+sum);
								
  return sum;
	    	}
	
public static void main(String[] args) {
Scanner sc= new Scanner(System.in);

	
System. out. println ("Enter your number: ");
	int n=sc.nextInt();
int result=check(n);
	if(n%result==0){
	    System. out. println ("Yes It Is a Harshad Number ");
	    	}
	    	else{
	    	    System. out. println ("No It Is Not a Harshad Numbe");
	    	}
 
}
}
//Question 7 //

//triangle area using herons formula//
import java.util.*;
import java.lang. Math;
class Main
{
    public static void main(String[] args)
    {
		Scanner sc = new Scanner(System.in);
 
System.out.println("Enter First side :");
		double  a = sc.nextDouble();        
		System.out.println("Enter Second side:");
		double b =sc.nextDouble();
		System.out.println("Enter third side :");
				double c=sc.nextDouble();
			
double s=(a+b+c) /2;
			double area =Math.sqrt(s*(s-a)*(s-b)*(s-c));
			System.out.println("area ="+ area);		  
    }  
}


//Question 8//

// vowel or consonant //

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

 System.out.print("Enter a character: ");
        char ch = scanner.next().charAt(0);
 if(ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u'
 
 ||ch=='A'||ch=='E'||ch=='I'||ch=='O'||ch=='U'
  ){
    System. out. println (" vowel")  ;}
    else if(ch>='a'&& ch<='z'|| ch>='A'&& ch<='Z'){
        System. out. println("consonant");}
   
else{
        System. out. println ("Invalid");}
    }
}

// Question 9//

//Quadratic //

import java.util.*;
import java. lang. Math. *;
class Main
{
    public static void main(String[] args)
    {
		Scanner sc = new Scanner(System.in);
 double r1=0;
 double r2= 0;
		System.out.println("Enter the First side :");
		double  a = sc.nextDouble();        
		System.out.println("Enter the Second side:");
		double b =sc.nextDouble();
		System.out.println("Enter the third side :");
			double c = sc.nextDouble();  
			
double d= b*b -4*a*c;
			if(d>0){
			    
  r1= (-b+Math.sqrt(d))/(2*a);
 r2= (b+Math.sqrt(d))/(2*a);	 
 
   System. out. println ("Roots are real");
          
System.out.println("Root1="+ r1+ " Root2 ="+r2);	    
			}
			
else if(  d==0){
			
 r1= -b/(2*a);
 	    
 System. out. println ("Roots are real and equal");	    
System.out.println("Root="+ r1 );		
						}	
			else {

 

System.out.println("Roots are imaginary");
 

}

}
			    
}


//Question 10//



import java. util. *;
class Student{
    String name;
    int age ;
    
//Using constructor
    public Student(String name,int age ){
        
 this.name =name ;
        this.age =age ;
          }
    
 public  void display(){
        
 System.out.println("Name =" + this.name);
        System.out.println ("Age =" + this.age);    
}
}
public class Main {
	public static void main(String[] args) {
Scanner sc =new Scanner(System.in) ;	   
System.out.println ("Enter your name: ");
 
   String name = sc. nextLine();
   System.out.println ("Enter your age :");
int age =sc.nextInt ();
	    
Student John =new Student(name, age);
	
John.display ();
		}
}



//Question 11..//

//method //
import java . util. *;

public class Main {

public static int addition ( int a, int b){
		int sum =a+b;
		 System. out. println ("sum = "+sum);
		return sum;
		
}
		
public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	
System. out. println ("Enter your first value");	
	int a= sc. nextInt();	
	
	
System. out. println ("Enter your second value");	
	int b= sc. nextInt();
		
addition(a, b) ;
		
}
}

//Question//










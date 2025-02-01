# Question-practice
Here I am practice coding question
         
          
          //start
         
// Find factors of a number

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


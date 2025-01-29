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


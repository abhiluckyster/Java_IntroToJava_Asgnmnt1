# Java_IntroToJava_Asgnmnt1
Introduction To Java Assignment 1

import java.util.Scanner;

public class SumOfTwoNo {

	public static void main(String args[]){
		float sum;
		Scanner numbers = new Scanner(System.in);
		
		System.out.println("Enter integer number");
		int num1=numbers.nextInt();
		
		System.out.println("Enter float number");
		float num2=numbers.nextFloat();
		
		sum=num1+num2;
		System.out.println("Sum of '"+num1+"' and '"+num2+"' is : "+sum);	
		
		numbers.close();
	}
}

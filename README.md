# Palindrome
I have done a Palindrome using java
Program:

import java.util.*;
public class Main
{
	public static void main(String[] args) {
		Scanner sc=new Scanner (System.in);
		int n=sc.nextInt();
		int s=0;
		int a=n;
		while(n>0){
		    s =s*10+n%10;
		    n =n/10;
		}
		if (s==a)
		        System.out.print("palindrom");
	else
	    System.out.print("not a palindrom");
	
}}

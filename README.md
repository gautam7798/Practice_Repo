# Practice_Repo
import java.io.*; 
public class Gautam
{ 
	public static void printPyramid(int n) 
	{ 
		int i, j; 

	 
		for(i=0; i<n; i++) 
		{ 	 
			for(j=0; j<=i; j++) 
			{ 
				System.out.print("* "); 
			}  
			System.out.println(); 
		} 
} 
	public static void main(String args[]) 
	{ 
		int n = 5; 
		printStars(n); 
	} 
} 

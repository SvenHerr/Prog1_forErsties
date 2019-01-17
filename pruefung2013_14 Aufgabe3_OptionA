package pruefung2013_14;

public class Aufgabe3_OptionB 
{
	public static int[] addiere(int []a, int [] b) 
	{
		for(int i = 0; i < a.length; i++) 
		{
			a[i] = a[i] + b[i];
		}
		
		for(int i = 0; i < a.length; i++) 
		{
			if(a[(a.length-1) - i] > 9)    
			{
				a[(a.length - 1) - i] -= 10;
				a[(a.length - 1) - (i+1)] += 1;
			}
		}
		return a;
	}
	
	public static void main(String[]args) 
	{
		int a[] = {3,4,2};
		int b[] = {6,2,9};
		
		int ergebnis [] = addiere(a,b);
		
		for(int i  = 0; i < ergebnis.length; i ++) 
		{
			System.out.println(ergebnis[i]);
		}
	}
}

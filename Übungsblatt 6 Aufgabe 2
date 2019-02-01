package uebungsblatt6;

import java.util.Scanner;

public class Aufgabe2 
{
	public static void main(String[] args) 
	{
		int zahl = 0;
		int zahl1 = 0;
		int ergebnis = 1;
		int temp = 1;
		Scanner scan = new Scanner(System.in);
		
		while(true)
		{
			zahl = scan.nextInt();
			zahl1 = zahl;
			if(zahl < 0 || zahl > 1000000) 
			{
				System.out.println("FEHLER – Zahl ist ungueltig.");
			}
			else if(zahl == 0) 
			{
				System.out.println("Das Querprodukt der Zahl " + zahl1 + " betraegt " + 0);
				break;
			}
			else 
			{
				while(zahl > 0 && zahl <= 1000000) 
				{
					temp = zahl % 10;
					zahl = zahl / 10;
					ergebnis = ergebnis * temp;
				}
				System.out.println("Das Querprodukt der Zahl " + zahl1 + " betraegt " + ergebnis);
				break;
			}
		}	
		scan.close();
	}
}

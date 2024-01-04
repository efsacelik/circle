# circle
Calculates area and perimeter of a circle.

package patikaAcademy;

import java.util.Scanner;

public class daireAlanCevre {

	public static void main(String[] args) {
		
		Scanner input = new Scanner(System.in);
		
		System.out.print("Dairenin yarıçapını giriniz: ");
		double radius = input.nextDouble();
		
		double pi=3.14 ,perimeter, area;
		
		perimeter= 2*pi*radius;
		area= pi*radius *radius;
		
		System.out.println("Dairenin alanı: "+ area);
		System.out.println("Dairenin çevresi: "+ perimeter);
		

	}

}

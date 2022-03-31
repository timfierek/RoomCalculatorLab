import java.util.Scanner;

public class Expressions {

	public static void main(String[] args) {
		boolean loop = true;
		Scanner in = new Scanner(System.in);
		
		System.out.println("Welcome to Grand Circus’ Room Detail Generator!\n");
	
		while(loop) {
			reqAndPrint(in);
			
			System.out.print("\nContinue? (y/n): ");
			if(in.next().equalsIgnoreCase("n")) {
				loop = false;
			}
		}
		
		in.close();
	}
		
	public static void reqAndPrint(Scanner in) {
		
		double len = -1;
		double width = -1;
		double height = -1;
		
		System.out.print("Enter Length: ");
		len = in.nextDouble();
		
		System.out.print("Enter Width: ");
		width = in.nextDouble();
		
		System.out.print("Enter height: ");
		height = in.nextDouble();
		
		double area = width * len;
		double perimeter = (2 * width) + (2 * len);
		double vol = area * height;
		
		System.out.println("Area: " + area );
		System.out.println("Perimeter: " + perimeter);
		System.out.println("Volume: " + vol);
			
	}
}



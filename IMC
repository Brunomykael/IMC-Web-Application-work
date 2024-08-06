import java.util.Scanner;

public class IMC {
	public static void main(String[] args) {
		Scanner scan = new Scanner(System.in);
		System.out.println("Digite O Seu Peso: ");
		float kg = scan.nextFloat();
		
		Scanner scan2 = new Scanner(System.in);
		System.out.println("Digite Sua Altura: ");
		float alt = scan2.nextFloat();
		
		double mat = kg/(alt * alt);
		
		System.out.println("Seu IMC é: " +mat);
		
		if (mat <= 18.5) {
			System.out.println("Magreza");
		}
		if (mat > 18.5 && mat < 24.9) {
			System.out.println("Normal");
		}
		if (mat > 24.9 && mat < 30) {
			System.out.println("Sobrepeso");
		}
		if (mat > 30) {
			System.out.println("Obesidade");
		}
	}	

}

package ExerciciosControle;

import java.util.Random;
import java.util.Scanner;

public class JogoAdvinhação {

	public static void main(String[] args) {
		
		int tentativas = 10;
		
		Scanner entry = new Scanner(System.in);
		
		Random random = new Random();
		int num1 = random.nextInt(100);
		
		do{
			System.out.print("Digite um número de 0 a 100: ");
			int num2 = entry.nextInt();
		
			if(num2 != num1 && num2 > num1) {
				System.out.println("Resposta errada, talvez você devesse tentar um número menor?");
			} else if(num2 != num1 && num2 < num1) {
				System.out.println("Resposta errada, talvez você devesse tentar um número maior?");
			} else {
				System.out.println("Resposta certa!");
				break;
			}
			tentativas--;
			System.out.println("----------------------");
			System.out.println("Tentativas restantes: " + tentativas);
		} while(tentativas != 0);
		
		
		if(tentativas > 0) {
			System.out.println("Parabéns!");
		} else {
			System.out.println("Mais sorte da próxima vez!");
		}
		
		entry.close();
	}

}

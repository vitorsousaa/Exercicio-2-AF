# Exercicio-2-AF
Exercicio 2 AF Imagem


1. matriz [l][c]=[16][16]
2. Escolha uma cor 
3.  Branco, Preto, Vermelho ou Bege
4. Enquanto l < 16 faça 
5. informe os elementos de acordo com a linha 
6. Enquanto c < 16 faça 
7. matriz [l][c]
8.  fim enquanto
9.   fim enquanto
10. Enquanto l < 16 faça
11. informe a linha
12. Enquanto c < 16
13. Exibe matriz [l][c]
14.  fim enquanto
15.   fim enquanto


package toad;

import java.util.Scanner;

public class toad {

	public static void main(String[] args) {
		Scanner batman = new Scanner(System.in);
		// criar variaveis
		int l, c, m[][] = new int[16][16];// criando matriz
		// Mostrar na tela
		System.out
				.println("Escolha as cores de acordo com o número\n-Branco = 0\n-Preto = 1\n-Vermelho = 2\n-Bege = 3");
		// Fazendo com que tenha uma  repetição
		for (l = 0; l < 16; l++) {
			// Mostrar na tela
			System.out.printf("Informe os elementos %da. linha:\n", (l + 1));
			for (c = 0; c < 16; c++) {
				System.out.printf("m[%d][%d] = ", l, c);
				m[l][c] = batman.nextInt(); // atribuindo valor digitado pelo usuario
			}
			// Espaço de linha 
			System.out.printf("\n");
		}
		System.out.printf("\n");
		for (l = 0; l < 16; l++) {
			System.out.printf("linha: ", (l + 1));
			for (c = 0; c < 16; c++) {
				System.out.printf("%d ", m[l][c]);
			}
			System.out.printf("\n");
		}

	}

}



![image](https://user-images.githubusercontent.com/103973613/173456537-fd7218ce-6ecc-4256-8ed4-02989a1d7ae3.png)

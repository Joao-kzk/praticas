# praticas
Só alguns exercicios q faço no tempo livre

cadastro e calculo de produto em java

import java.util.Scanner;

public class MyClass {
  public static void main(String args[]) {
    Scanner scanner = new Scanner(System.in);
    System.out.print("Digite o nome do produto: ");
        String nome = scanner.nextLine();

        System.out.print("Digite seu preço: ");
        double preço = scanner.nextDouble();

        System.out.print("Digite a quantidade: ");
        int quantidade = scanner.nextInt();
        
        double total = (preço * quantidade);
        System.out.printf("Valor total da compra: R$ %.2f\n", total);
        
        if (total >= 100) {
            System.out.print("Parabéns voce ganhou frete");
            
        } else {
            System.out.print("frete nao incluso");
        }
        
  }
}

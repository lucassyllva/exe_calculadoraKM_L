# calculadoraKM_L.emJAVA
import java.util.Scanner;

public class calculadoraConsumo {
    public static void main (String[] args){
  
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("informe o consumo de combustivel em KM/L ");
        double consumo =scanner.nextDouble();

        System.out.print("Digite o preço do litro de combustível: R$");
        double precoLitro =scanner.nextDouble();

        System.out.print("Digite a distância percorrida em quilômetros: ");
        double distancia =scanner.nextDouble();

        double litrosNecessarios = distancia / consumo;

        double precoTotal = litrosNecessarios * precoLitro;

        System.out.println("O preço total do combustível é: R$" + precoTotal);

        scanner.close();


    }

    
}

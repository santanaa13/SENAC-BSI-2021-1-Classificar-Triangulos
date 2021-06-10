# Classificação de Triângulos

Escreva um algoritmo em Java que solicite ao 
usuário a entrada de 3 números. Considere que
estes números são os lados de um triângulo.

Seu algoritmo deverá:

1. Indicar se "realmente" são lados de um triângulo
2. Se os lados compõem um triângulo, identifique 
   qual sua classificação: 
   - Equilátero
   - Isósceles
   - Escaleno

Sua resposta deverá ser enviada através de um PULL REQUEST
a este repositório.






import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner leitor = new Scanner(System.in);
        System.out.println ("Qual o Valor do Primeiro Lado do Triângulo?");
float lado1 = leitura.nextFloat ();
System.out.println ("Segundo Lado do Triangulo");
float lado2 = leitura.nextFloat ();
System.out.println ("Terceiro Lado do Triangulo");
float lado3 = leitura.nextFloat ();

float triangulo;
if (lado1 <lado2) {
triangulo = lado1; 
lado1 = lado2; 
lado2 = triangulo; 
}

if (lado2 <lado3) {
triangulo = lado2; 
lado2 = lado3;
lado3 = triangulo; 
                              }

if (lado1 <lado2) {
triangulo = lado1;
lado1 = lado2;
lado2 = triangulo;

}

System.out.println ("Lado A:" + lado1 + "\ nLado B:" + lado2 + "\ nLado C:" + lado3);


if (lado1> = (lado2 + lado3)) {
System.out.println ("Isso não forma um Triangulo");
}

 senão{

if (lado1 == lado2 && lado2 == lado3) {
System.out.println ("Forma um Triangulo Equilatero");
}

else if (lado1 == lado2 || lado1 == lado3 | lado2 == lado3) {
System.out.println ("Forma um Triangulo Isosceles");
}

else if (lado1! = lado2 || lado1! = lado3 | lado2! = lado3) {
System.out.println ("Forma um Triangulo Escaleno");
}

        }
   }
}

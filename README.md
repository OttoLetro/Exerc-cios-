       Exercícios de Programação
1. Faça um programa que receba três notas, calcule e mostre a média aritmética entre elas.
Algoritimo:
import java.util.Scanner;
public class media {
    public static void main(String args[]) {
        int N1, N2, N3, Media;
        Scanner input = new Scanner(System.in);
        System.out.print("digite o primeiro numero");
        N1 = input.nextInt();
        System.out.print("digite o segundo numero");
        N2 = input.nextInt();
        System.out.print("digite o terceiro numero");
        N3 = input.nextInt();
        Media = (N1 + N2 + N3) / 3;
        System.out.print("A media e:" + Media);
    }}
4. Faça um programa que receba o salário de um funcionário, calcule e mostre o novo salário, sabendo-se que este sofreu um aumento de 25%.
Algoritimo:
import java.util.Scanner;
public class salario {
    public static void main(String args[]) {
        Scanner input = new Scanner(System.in);
        float salario, novoSalario, totalSalario;
        System.out.println("digite o salario");
        salario = input.nextFloat();
        novoSalario = salario * .25f;
        totalSalario = salario + novoSalario;
        System.out.println("O salario + novoSalario e:" + totalSalario);
    }}
5. Faça um programa que calcule e mostre a área de um losango AREA = (DIAGONAL MAIOR *DIAGONAL MENOR)/2
Algoritimo:
import java.util.Scanner;
public class losango {
    public static void main(String args[]) {
        Scanner input = new Scanner(System.in);
        double diagonalM, diagonalm, area;
        System.out.println("Digite a diagonalM :");
        diagonalM = input.nextDouble();
        System.out.println("Digite a diagonalm: ");
        diagonalm = input.nextDouble();
        area = (diagonalM * diagonalm) / 2;
        System.out.println("A area e:" + area);
    }}
8. Faça um programa que receba o peso de uma
pessoa, calcule e mostre:
a) O seu novo peso, se a pessoa engordar 15% sobre o peso digitado
b) O seu novo peso, se a pessoa emagrecer 20% sobre o peso digitado
import java.util.Scanner;
public class Main {
    public static void main(String args[]){
        Scanner input = new Scanner (System.in);
         double peso, engordar, emagrecer;
         System.out.print("Digite o seu peso: ");
         peso=input.nextInt();
         engordar = peso * 1.15;
         emagrecer = peso * 0.8;
         System.out.println("O seu peso apos engordar é:"+engordar);
         System.out.println("O seu peso apos emagrecer é:"+emagrecer)
}}
9. Faça um programa que receba o valor dos catetos de um triângulo, calcule e mostre o valor da hipotenusa.
Algoritimo:
//a^2 + b^2 =c^2 teorema de pitágoras.
import java.util.Scanner;
public class Pitagoras {
    public static void main(String args[]) {
        Scanner input = new Scanner(System.in);
        double cat1, cat2, hipotenuza;
        System.out.println("Digite cat1: ");
        cat1 = input.nextDouble();
        System.out.println("Digite ca2: ");
        cat2 = input.nextDouble();
        // hipotenuza= C^2
        hipotenuza = (cat1 * cat1) + (cat2 * cat2);
        System.out.println("Hipotenuza e:" + hipotenuza);
}}
10. Faça um programa que receba o raio, calcule
e mostre: O comprimento de uma esfera (C = 2 * π * R) A área de uma esfera (A = π * R2) O volume de uma esfera (V = ¾ * π * R3
algoritimo:
import java.util.Scanner;
public class exer10 {
    public static void main(String args[]) {
        Scanner input = new Scanner(System.in);
        double C, A, V, R;
        System.out.print("Digite o valor do raio: ");
        R = input.nextInt();
        C = 2 * 3 * R;
        A = 3 * (Math.pow(R, 2));
        V = 0.75 * 3 * (Math.pow(R, 3));
        System.out.println("O valor do comprimento é: " + C);
        System.out.println("O valor da área é: " + A);
        System.out.println("O valor do volume é:" + V);
    }}
11. Faça um programa que solicite ao usuário
que informe os coeficientes a, b e c de uma
equação de segundo grau, e que imprima as
raízes desta equação (considere que os
valores informados sempre retornarão raízes
reais para a equação).
Algoritimo:
import java.util.Scanner;
public class raiz {
    public static void main(String args[]) {
        Scanner input = new Scanner(System.in);
        double a, b, c, D, x1, x2;
        System.out.print("Digite o valor de a: ");
        a = input.nextDouble();
        System.out.print("Digite o valor de b: ");
        b = input.nextDouble();
        System.out.print("Digite o valor de c: ");
        c = input.nextDouble();
        D = (Math.pow(b, 2)) - 4 * a * c;
        x1 = (-b + (Math.sqrt(D))) / 2 * a;
        x2 = (-b - (Math.sqrt(D))) / 2 * a;
        System.out.println("O valor de x1 é:" + x1);
        System.out.println("O valor de x2 é:" + x2);
}
}
12. Faça um programa que calcule e mostre a
tabuada de multiplicação de um número
digitado pelo usuário
Algoritimo:
import java.util.Scanner;

public class calculadora {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        double n, x;
        System.out.print("Digite o numero desejado: ");
        n = input.nextInt();
        System.out.println();
        for (x = 1; x <= 10; x++) {
            System.out.print("Tabuada do: " + n);
            System.out.print(x + " = ");
            System.out.println(x * n);
        }
}
}

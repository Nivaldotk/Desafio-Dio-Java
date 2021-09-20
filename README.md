# Desafio-Dio-Java
Primeiro Desafio empregado pela Dio sobre a linguagem JAVA


# Primeiro Desafio 
Desafio Duas motos (X e Y) partem em uma mesma direção. A moto X sai com velocidade constante de 60 Km/h e a moto Y sai com velocidade constante de 90 Km/h. Em uma hora (60 minutos) a moto Y consegue se distanciar 30 quilômetros da moto X, ou seja, consegue se afastar um quilômetro a cada 2 minutos. O seu desafio é ler a distância (em Km) e calcular quanto tempo leva (em minutos) para a moto Y tomar essa distância da outra moto.

Entrada O arquivo de entrada contém um número inteiro K que representa a quantidade de quilômetro que que a moto Y deve estar da moto X.

Saída Imprima o tempo necessário para a moto Y ficar com a quantidade K de quilômetro da moto X, seguido da mensagem " minutos".

#Segundo Desafio 

import java.util.Scanner;
public class Main{
public static void main(String[] args){
Scanner in = new Scanner(System.in);
int A = in.nextInt();
int B = in.nextInt();
int SOMA = A+B;
System.out.println("SOMA = "+SOMA);
}
}

#Terceiro Desafio 
Dividindo x por y

import java.util.Scanner;
public class Divisao {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int n = input.nextInt();
        for (int i = 0; i < n; i++) {
            double  x = input.nextDouble();
            double y = input.nextDouble();

            if (y == 0) {
                System.out.println("divisao impossivel");
            } else {
                double divisao = x / y;
                System.out.printf("%.1f\n", divisao);
            }
        }

    }
}

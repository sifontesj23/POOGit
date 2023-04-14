<hr>


## Atv01

> passos realizados para a resolução da atividade. 
    Foi feito a importaçao uyil.Scaner
    cre as clases atv01 e o metodo main(String)
    creamos variaves nun, num2, soma
    scaneamos do usuario os numeros  almacenandos em variaves e logo somamos, a soma pode ser qualquer numero real.
    logo mostramos na tela com println a soma.


>  código Java criado para a resolução da atividade.
package atv01;

import java.util.Scanner;

public class atv01 {
    public static void main(String [] args) {
        double num, num2, soma;
    
        Scanner sc = new Scanner(System.in);
        System.out.println("Digite numero 1");
        num = sc.nextDouble();

        System.out.println("Digite numero 2");
        num2 = sc.nextDouble();

        soma= num + num2;

        System.out.println("soma dos numero:" + soma);
    }
}

<hr>


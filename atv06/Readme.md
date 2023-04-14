Act 06

Codigo Desenvolvido


package atv06;
import java.util.Scanner;

public class atv06 {
    public static void main(String[] args) {

        float meta, deposito, acumulado,juros = 0.5f ;
        int meses=1;
        /* */       
        System.out.println ("Digite o monto que você quer acumular");
        Scanner ac = new Scanner(System.in);
        meta = ac.nextFloat();
        System.out.println ("quer acumular:" + meta);

        System.out.println ("Digite o monto que você quer depositar fixo Mensual ");
        Scanner dpScanner = new Scanner(System.in);
        deposito = dpScanner.nextFloat();
        System.out.println ("quer depositar fixo mensual: " + deposito);
        acumulado=0;

        System.out.println ("Lembrando que a taxa de juro mensual ê: " + juros);
        
        if (meta>deposito){
          while (meta>acumulado) {
            acumulado = acumulado*1.05f+deposito;
            
            meses++;
            System.out.println("o mes nro " + meses + " leva acumulado: " + acumulado + "reais ");
            
          }
          System.out.println ("Fim Voce demorou:" + meses + " meses," + " su meta era: " + meta + " e acumulo: " + acumulado);
        } else {
          System.out.println("Voce ja tem o valor desejado Sõ com o primer deposito.");
        }
               
    }
}

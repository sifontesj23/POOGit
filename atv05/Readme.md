Atv 05

Codigo Desenvovido

package atv05;

public class atv {
    public static void main(String[] args) {
        double gastosJaneiro ;
        gastosJaneiro= 33000.00;
        double gastosFevereiro;
        gastosFevereiro=33030.77;
        double gastosMarco;
        gastosMarco = 23899.01;
        double gastosTrimestre=gastosJaneiro + gastosFevereiro + gastosMarco;
        System.out.println(gastosTrimestre);
        double mediaMensual;
        mediaMensual= gastosTrimestre/3;
        System.out.println("Valor da media mensual= " + mediaMensual);

    }
}

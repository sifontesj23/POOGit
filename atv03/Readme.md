/*Usando a classe JOptionPane para entrada de dados, crie uma classe que receba a nota de
duas provas e de um trabalho. Calcule e mostre a média.*/

package atv03;

import javax.swing.JOptionPane  ;

public class atv03 {
    public static void main(String[] args) {
        Float prova1, prova2, trabalho, media;

        prova1 = Float.parseFloat(JOptionPane.showInputDialog("Digite nota prova 1"));
        prova2 = Float.parseFloat(JOptionPane.showInputDialog("Digite nota prova 2"));
        trabalho = Float.parseFloat(JOptionPane.showInputDialog("Digite nota Trabahlo"));

       media = (prova1 + prova2 + trabalho)/3;

       JOptionPane.showMessageDialog(null, "a media =" + media);
    
       

    }
}

# Ejercicio3DAM113
package examen.ejercicio3;

/**
 *
 * @author DAM113
 */
public class Ejercicio3 {

    public static void main(String[] args) {
       String frase="Me llamo Leila Fraile Simon";
       int conEspacios=frase.length();
        System.out.println("Longitud de la frase con espacios: "+conEspacios);
        int sinEspacios=frase.replace("","").length();
        System.out.println("La frase tiene: "+sinEspacios + "letras");
    }
}

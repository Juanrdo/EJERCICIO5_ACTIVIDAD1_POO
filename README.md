# EJERCICIO5_ACTIVIDAD1_POO

package circuloconr;
import java.util.Scanner;
public class Circuloconr {

    public static void main(String[] args) {
        double  radio,area,longitud;
        Scanner teclado = new Scanner (System.in);
        
        System.out.println("Ingrese el radio del circulo:  ");
        radio = teclado.nextDouble();
        area= Math.PI * Math.pow (radio,2);
        longitud= 2* Math.PI * radio;
        
        System.out.println("el radio es: "+ radio);
        System.out.println("el area es :  "+ area);
        System.out.println("la longitud es :  "+ longitud);
        
        
                
    }
    
}

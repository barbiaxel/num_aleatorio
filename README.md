# num_aleatorio
Número aleatorio entre 100 y 200 y nos dice si es par o impar
package ejercicio4;
import java.util.Random;
//numero aleatorio entre 100 y 200 y nos dice si es par o impar
public class ejercicio4 {

	public static void main(String[] args) {
		Random rnd = new Random();
		int valor = 0;
		for(int i = 1; i<=1; i++)
		     valor = (rnd.nextInt(200-100+1)+100);
		System.out.println ("El número aleatorio generado entre 100 y 200 es: "+valor);
		
			if (valor % 2 == 0 ) {
				System.out.println("El número es par."); 
			} else {
					System.out.println("El número es impar.");
					}
	}

}

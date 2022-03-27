# POO-1

## Guía 2 - Java
### Ejercicio 1
````
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
	    float precioUnitario, importeCompra, importeDescuento, importePagar;
        int cantidadUnidades;
        System.out.println("Digite el precio unitario: ");
        precioUnitario = scanner.nextFloat();
        System.out.println("Digite la cantidad de unidades: ");
        cantidadUnidades = scanner.nextInt();
        importeCompra = precioUnitario * cantidadUnidades;
        importeDescuento = importeCompra * 0.15F;
        importePagar = importeCompra - importeDescuento;
        System.out.println("El importe de la compra es: " + importeCompra);
        System.out.println("El importe del descuento es: " + importeDescuento);
        System.out.println("El importe a pagar es: " + importePagar);
    }
}
````
### Ejercicio 2
````
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
	    float precionormal, precioSSanta, importeTotal;
        int cantidadPasajes, cantidadChocolates;
        System.out.println("Digite el precio normal del pasaje: ");
        precionormal = scanner.nextFloat();
        System.out.println("Digite la cantidad de pasajes adquiridos: ");
        cantidadPasajes = scanner.nextInt();
        precioSSanta = precionormal + (precionormal * 0.35F);
        importeTotal = precioSSanta * cantidadPasajes;
        cantidadChocolates = 3 * cantidadPasajes;
        System.out.println("El precio del pasaje por Semana Santa es: " + precioSSanta);
        System.out.println("El importe total a pagar es: " + importeTotal);
        System.out.println("La cantidad de chocolates de obsequio es: " + cantidadChocolates);

    }
}
````


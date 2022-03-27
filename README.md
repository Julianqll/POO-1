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

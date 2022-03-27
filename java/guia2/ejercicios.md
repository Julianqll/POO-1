# Ejercicio 1
```
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
```
# Ejercicio2

```
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
```
# Ejercicio 3

```
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        float precioDocena, costoTransporte, importeCompra,  importeDescuento, importeTotal;
        int docenasAdquiridas;
        Scanner scanner = new Scanner(System.in);
        System.out.println("Digite el precio por docena: ");
        precioDocena = scanner.nextFloat();
        System.out.println("Digite la cantidad de docenas adquiridas: ");
        docenasAdquiridas = scanner.nextInt();
        System.out.println("Digite el costo del transporte: ");
        costoTransporte = scanner.nextFloat();
        importeCompra = precioDocena * docenasAdquiridas;
        importeDescuento = importeCompra * 0.12F;
        importeTotal = importeCompra - importeDescuento + costoTransporte;
        System.out.println("El importe de la compra es: " + importeCompra);
        System.out.println("El importe de descuento es: " + importeDescuento);
        System.out.println("El importe a pagar es: " + importeTotal);
    }
}
```

# Ejercicio 4

```
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
	    float precioUnitario , primerDescuento, segundoDescuento, importeCompra, importeDesctotal, importePagar;
        int cantidadUnidades;
        Scanner scanner = new Scanner(System.in);
        System.out.println("Digite el precio unitario: ");
        precioUnitario = scanner.nextFloat();
        System.out.println("Digite la cantidades de unidades adquiridas: ");
        cantidadUnidades = scanner.nextInt();
        importeCompra = precioUnitario * cantidadUnidades;
        primerDescuento = importeCompra * 0.1F;
        segundoDescuento = (importeCompra - importeCompra * 0.1F) * 0.1F;
        importeDesctotal = primerDescuento + segundoDescuento;
        importePagar = importeCompra - importeDesctotal;
        System.out.println("El importe de la compra es: " + importeCompra);
        System.out.println("El importe del descuento total es: " + importeDesctotal);
        System.out.println("El importe a pagar es: " + importePagar);
    }
}
```
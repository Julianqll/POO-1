# Ejercicio 1
```
#include<iostream>

using namespace std;

int main(){
	float punit, unidad, importe = 0, descuento = 0, pfinal = 0;
	cout<<"Digite el precio unitario en soles: ", cin>>punit;
	cout<<"Digite la cantidad que va a adquirir: ", cin>>unidad;
	
	importe = punit * unidad;
	descuento = importe * 0.15;
	pfinal = importe - descuento;
	
	cout<<"El importe de la compra es "<<importe, cout<<" soles.\n";
	cout<<"El descuento es "<<descuento, cout<<" soles.\n";
	cout<<"El importe a pagar es "<<pfinal, cout<<" soles.";
	
	return 0;
} 
```
# Ejercicio2

```
#include<iostream>

using namespace std;

int main(){
	float pnormal, cantidad, pfinal = 0, importe = 0, chocolate = 0;
	cout<<"Digite el precio normal de cada pasaje en soles: ", cin>>pnormal;
	cout<<"Digite la cantidad de pasajes adquiridos: ", cin>>cantidad;
	
	pfinal = pnormal * 1.35;
	importe = pfinal * cantidad;
	chocolate = cantidad * 3;
	
	cout<<"El precio de cada pasaje por Semana Santa es de "<<pfinal, cout<<" soles.\n";
	cout<<"El importe total a pagar es de "<<importe, cout<<" soles.\n";
	cout<<"Se le obsequia "<<chocolate, cout<<" chocolates.";
	
	return 0;
}


```
# Ejercicio 3

```
#include<iostream>

using namespace std;

int main(){
	float docena, cantidad, transporte, costo = 0, descuento = 0, importe = 0;
	
	cout<<"Digite el precio por docena de cuadernos en soles: ", cin>>docena;
	cout<<"Digite la cantidad de docenas adquiridas: ", cin>>cantidad;
	cout<<"Digite el costo por transporte en soles: ", cin>>transporte;
	
	costo = docena * cantidad;
	descuento = costo * 0.12;
	importe = costo - descuento + transporte;
	
	cout<<"El importe de la compra es "<<costo, cout<<" soles.\n";
	cout<<"El descuento es "<<descuento, cout<<" soles.\n";
	cout<<"El importe a pagar (incluyendo transporte) es "<<importe, cout<<" soles.";
	
	return 0;
}
```

# Ejercicio 4

```
#include<iostream>

using namespace std;

int main(){
	float punitario, cantidad, costo = 0, descuento1 = 0, descuento2 = 0, importe = 0;
	
	cout<<"Digite el precio unitario del producto en soles: ", cin>>punitario;
	cout<<"Digite la cantidad adquirida: ", cin>>cantidad;
	
	costo = punitario * cantidad;
	descuento1 = costo * 0.10;
	descuento2 = descuento1 * 0.10;
	importe = costo - descuento2;
	
	cout<<"El importe de la compra es "<<costo, cout<<" soles.\n";
	cout<<"El descuento total es "<<descuento2, cout<<" soles.\n";
	cout<<"El importe a pagar es "<<importe, cout<<" soles.";
	
	return 0;
}

```

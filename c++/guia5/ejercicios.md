# Ejercico 1
```c++
#include <iostream>

using namespace std;

int main()
{
    int cantidad;
    float importe_compra,precio_unidad,descuento,importe_pagar;
    cout<<"Precio de unidad: ";cin>>precio_unidad;
    cout<<"Cantidad: ";cin>>cantidad;
    importe_compra=precio_unidad*cantidad;
    descuento=importe_compra*0.15;
    importe_pagar=importe_compra-descuento;

    cout<<"Importe de compra: "<<importe_compra<<endl;
    cout<<"Importe de descuento: "<<descuento<<endl;
    cout<<"Importe a pagar: "<<importe_pagar;
    return 0;
}
```
# Ejercico 2
```c++
#include <iostream>

using namespace std;

int main()
{
   float importe_compra,importe_pagar,descuento,precio_boleto;
   int cantidad,chocolates;
   cout<<"Precio de boleto: ";cin>>precio_boleto;
   cout<<"Cantidad:  ";cin>>cantidad;


   importe_compra=precio_boleto*cantidad;
   descuento=importe_compra*0.07;
   importe_pagar=importe_compra-descuento;
   chocolates=cantidad*3;
   
   cout<<"Importe a compra: "<<importe_compra<<endl;
   cout<<"Importe del descuento: "<<descuento<<endl;
   cout<<"Importe a pagar: "<<importe_pagar<<endl;
   cout<<"Cantidad de chocolates: "<<chocolates<<endl;
   return 0;
}
```
# Ejercico 3
```c++
#include <iostream>

using namespace std;

int main()
{
    float descuento_1,descuento_2,descuento_total,importe_compra,importe_pagar,precio_producto,cantidad;

    cout<<"Cantidad: ";cin>>cantidad;
    cout<<"Precio del producto: ";cin>>precio_producto;

    importe_compra=precio_producto*cantidad;
    descuento_1=importe_compra*0.10;
    descuento_2=(importe_compra-descuento_1)*0.10;
    importe_pagar = (importe_compra-descuento_1) - descuento_2;
    descuento_total=descuento_1+descuento_2;

    cout<<"Importe a comprar : "<<importe_compra<<endl;
    cout<<"Importe de descuento : "<<descuento_total<<endl;
    cout<<"Importe de pagar: "<<importe_pagar;

   return 0;
}
```
# Ejercico 4
```c++

#include <iostream>

using namespace std;

int main()
{
    int horas_trabajas;
    float tarifa_horaria,descuento,sueldo_bruto,sueldo_neto;

    cout<<"Cantidad de horas trabajadas: ";cin>>horas_trabajas;
    cout<<"Tarifa horaria: ";cin>>tarifa_horaria;
    
    sueldo_bruto=tarifa_horaria*horas_trabajas;

    descuento=sueldo_bruto*0.15;

    sueldo_neto=sueldo_bruto-descuento;


    cout<<"Sueldo bruto: "<<sueldo_bruto<<endl;
    cout<<"Descuento del 15% :"<<descuento<<endl;
    cout<<"Sueldo neto: "<<sueldo_neto<<endl;

   return 0;
}

```
# Ejercico 5
```c++
#include<iostream>

using namespace std;

int main()
{
	float descuento,total_vendido,sueldo_basico=350.75,sueldo_bruto,comision,sueldo_neto;
	
	cout<<"Cuanto has vendido: ";cin>>total_vendido;
	comision=total_vendido*0.05;
	sueldo_bruto=sueldo_basico+comision;
	
	descuento=sueldo_bruto*0.15;
	
	sueldo_neto=sueldo_bruto-descuento;
	cout<<"Sueldo basico: "<<sueldo_basico<<endl;
	cout<<"Comision: "<<comision<<endl;
	cout<<"Sueldo bruto: "<<sueldo_bruto<<endl;
	cout<<"Descuento: "<<descuento<<endl;
	cout<<"Sueldo neto: "<<sueldo_neto<<endl;
	return 0;
}
```
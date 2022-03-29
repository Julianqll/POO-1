# Ejercicio1

````c++
#include <iostream>

using namespace std;

int main()
{

    float promedio_ponderado;

    cout<<"Digite el promedio: ";cin>>promedio_ponderado;

    if(promedio_ponderado>=17)
    {
        cout<<"Categoria A";
    }
    else if(promedio_ponderado>=14&&promedio_ponderado<17)
    {
        cout<<"Categoria B";
    }
    else if(promedio_ponderado>=12&&promedio_ponderado<14)
    {
        cout<<"Categoria C";
    }
    else if(promedio_ponderado<12)
    {
        cout<<"Categoria D";
    }

    return 0;
}
````


# Ejercicio2

````c++
#include<iostream>
#include<string.h>
using namespace std;
float descuento;
void Descuento(float ,int);
void Descuento(float Importe_compra, int Cantidad_litros)
{
    if(Cantidad_litros>=10)
    {
        cout<<"Descuento: 12.5%"<<endl;
        descuento=Importe_compra*0.125;
    }
    else if(Cantidad_litros>=7&&Cantidad_litros<10)
    {
        cout<<"Descuento: 10.0%"<<endl;
        descuento=Importe_compra*0.10;
    }
    else if(Cantidad_litros>=4&&Cantidad_litros<7)
    {
        cout<<"Descuento: 7.5%"<<endl;
        descuento=Importe_compra*0.075;
    }
    else
    {
        cout << "Descuento: 5.0%" << endl;
        descuento = Importe_compra * 0.05;
    }
}
int main()
{
    //con string no funciono
    char Codigo[99];
    float Precio_litro,Importe_compra;
    cout << "Ingrese el codigo: ";cin.getline(Codigo, 99);
    strlwr(Codigo);
    int Cantidad_litros;
    cout<<"Ingrese la cantidad de litros: ";cin>>Cantidad_litros;
    if (strcmp(Codigo, "primor") == 0)
    {
        Precio_litro=5.99;
        cout<<"Precio por litro: S/."<<Precio_litro<<endl;
        Importe_compra=Precio_litro*Cantidad_litros;
        Descuento(Importe_compra,Cantidad_litros);
        cout<<"Importe a pagar "<<Importe_compra-descuento;
    }
    else if (strcmp(Codigo, "girasol") == 0)
    {
        Precio_litro=5.50;
        cout<<"Precio por litro: S/."<<Precio_litro<<endl;
        Importe_compra=Precio_litro*Cantidad_litros;
        Descuento(Importe_compra,Cantidad_litros);
        cout<<"Importe a pagar "<<Importe_compra-descuento;
    }
    else if (strcmp(Codigo, "cil") == 0)
    {
        Precio_litro=4.50;
        cout<<"Precio por litro: S/."<<Precio_litro<<endl;
        Importe_compra=Precio_litro*Cantidad_litros;
        Descuento(Importe_compra,Cantidad_litros);
        cout<<"Importe a pagar "<<Importe_compra-descuento;
    }
    else if (strcmp(Codigo, "cocinero") == 0)
    {
        Precio_litro=4.70;
        cout<<"Precio por litro: S/."<<Precio_litro<<endl;
        Importe_compra=Precio_litro*Cantidad_litros;
        Descuento(Importe_compra,Cantidad_litros);
        cout<<"Importe a pagar "<<Importe_compra-descuento;
    }
    else
    {
        cout<<"Esa marca no existe";
    }
    return 0;
}
````


# Ejercicio3
````c++
#include<iostream>
#include<string.h>
using namespace std;
float descuento;
void Descuento(float ,int);
void Descuento(float Importe_compra, int Cantidad_litros)
{
    if(Cantidad_litros<15)
    {
        cout<<"Descuento: 4.0%"<<endl;
        descuento=Importe_compra*0.125;
    }
    else if(Cantidad_litros>=15&&Cantidad_litros<30)
    {
        cout<<"Descuento: 6.5%"<<endl;
        descuento=Importe_compra*0.10;
    }
    else if(Cantidad_litros>=30&&Cantidad_litros<45)
    {
        cout<<"Descuento: 9.0%"<<endl;
        descuento=Importe_compra*0.075;
    }
    else
    {
        cout << "Descuento: 11.5%" << endl;
        descuento = Importe_compra * 0.05;
    }
}
int main()
{
    //con string no funciono
    char Codigo[99];
    float Precio_litro,Importe_compra;
    cout << "Ingrese el codigo: ";cin.getline(Codigo, 99);
    strlwr(Codigo);
    int Cantidad_litros;
    cout<<"Ingrese la cantidad de litros: ";cin>>Cantidad_litros;
    if (strcmp(Codigo, "laive") == 0)
    {
        Precio_litro=3.90;
        cout<<"Precio por litro: S/."<<Precio_litro<<endl;
        Importe_compra=Precio_litro*Cantidad_litros;
        Descuento(Importe_compra,Cantidad_litros);
        cout<<"Importe a pagar "<<Importe_compra-descuento;
    }
    else if (strcmp(Codigo, "gloria") == 0)
    {
        Precio_litro=3.80;
        cout<<"Precio por litro: S/."<<Precio_litro<<endl;
        Importe_compra=Precio_litro*Cantidad_litros;
        Descuento(Importe_compra,Cantidad_litros);
        cout<<"Importe a pagar "<<Importe_compra-descuento;
    }
    else if (strcmp(Codigo, "pura vida") == 0)
    {
        Precio_litro=4.20;
        cout<<"Precio por litro: S/."<<Precio_litro<<endl;
        Importe_compra=Precio_litro*Cantidad_litros;
        Descuento(Importe_compra,Cantidad_litros);
        cout<<"Importe a pagar "<<Importe_compra-descuento;
    }
    else if (strcmp(Codigo, "milkito") == 0)
    {
        Precio_litro=3.60;
        cout<<"Precio por litro: S/."<<Precio_litro<<endl;
        Importe_compra=Precio_litro*Cantidad_litros;
        Descuento(Importe_compra,Cantidad_litros);
        cout<<"Importe a pagar "<<Importe_compra-descuento;
    }
    else
    {
        cout<<"Esa marca no existe";
    }
    return 0;
}
````

# Ejercicio4
````c++
#include<iostream>
#include<math.h>
using namespace std;


int main()
{
    float IMC,peso,estatura;


    cout<<"Digite su peso en kilogramos: ";cin>>peso;
    
    cout<<endl<<"Digite su estatura en metros: ";cin>>estatura;
    
    IMC=peso/pow(estatura,2);cout<<"Indice de masa corporal: "<<IMC<<endl;
    
    cout<<"Peso en kilogramos: "<<peso<<endl;
    
    cout<<"Estatura en metros: "<<estatura<<endl;
    
    if(IMC<20)
    {
        cout<<"Grado de obesidad: Delgado";
    }
    else if(IMC>=20&&IMC<25)
    {
        cout<<"Grado de obesidad: Normal";
    }
    else if(IMC>=25 &&IMC<27)
    {
        cout<<"Grado de obesidad: Sobrepeso";
    }
    else if(IMC>=27)
    {
        cout<<"Grado de obesidad: Obesidad";
    }

    return 0;
}
````


# Ejercicio 1
```c++
#include<iostream>

using namespace std;

int main()
{
    int num[10],numero,index=0;
	
    for(int i=0;i<10;++i)
    {
        cout<<"Numero: ";cin>>numero;
        if(numero>=0)
        {
            num[index] = numero;
            index++;
        }
    }
	for(int i=0;i<index;i++)
    {
        cout<<num[i]<<" ";
    }
    return 0;
}
```
# Ejericicio 2
```c++
#include<iostream>

using namespace std;

int main()
{
    float calficacion,promedio=0;
    for(int i=0;i<7;i++)
    {
        cout<<"Digite la calificacion "<<i+1<<": ";cin>>calficacion;
        promedio+=calficacion;
    }
    promedio/=7;
    cout<<"\nEl promedio del alumno es: "<<promedio;
    return 0;
}
```
# Ejericicio 3
```c++
#include<iostream>

using namespace std;

int main()
{
    int n;
    float calificacion[999],calificacion_media=0,calificacion_baja=NULL;

    cout<<"Digite la cantidad de alumnos: ";cin>>n;

    for(int i=0;i<n;i++)
    {
        cout<<"Digite la calificacion: ";cin>>calificacion[i];
        calificacion_media+=calificacion[i];
        if(calificacion_baja==NULL)
        {
            calificacion_baja=calificacion[i];
        }
        else if(calificacion_baja>calificacion[i])
        {
            calificacion_baja=calificacion[i];
        }
    }
    calificacion_media/=n;

    cout<<"Calificacion media: "<<calificacion_media<<endl;
    cout<<"Calificacion mas baja: "<<calificacion_baja;

    return 0;
}
```
# Ejericicio 4
```c++
#include <iostream>

using namespace std;

int main()
{
    float salarios_obreros[999];
    //lo transformo en float por que necesito trabajar con decimales
    float cantidad_horas;
    int n;
    cout<<"Digite la cantidad de obreros: ";
    cin>>n;

    for(int i=0;i<n;i++)
    {
        cout<<"Digite la cantidad de horas trabajadas por el obrero "<<i+1<<": ";cin>>cantidad_horas;
        if(cantidad_horas<=40)
        {
            salarios_obreros[i]=cantidad_horas*20;
        }
        else
        {
            salarios_obreros[i]=40*20;
            salarios_obreros[i]+=(cantidad_horas-40)*20;
        }

    }
    for(int i=0;i<n;i++)
    {
        cout<<"Pago de obrero "<<i+1<<": "<<"S/."<<salarios_obreros[i]<<endl;
    }
    return 0;
}

```
# Ejericicio 5
```c++
#include <iostream>

using namespace std;

int main()
{
    float arr[999],mayor=NULL;
    int n;
    cout<<"Digite la cantidad de numeros: ";
    cin>>n;
    for(int i=0;i<n;i++)
    {
        cout<<"Digite el numero: ";
        cin>>arr[i];
        if(mayor==NULL)
        {
            mayor=arr[i];
        }
        else if(mayor<arr[i])
        {
            mayor=arr[i];
        }
    }
    cout<<"\nMayor numero: "<<mayor;
    return 0;
}

```
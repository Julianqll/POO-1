# Tareas Semana 1 - POO I 
## Integrantes:
- Alexander Rivera Rimac
- Andrés Daniel Galvan Oyague
- Fabian imanol Ojeda Valero
- Julian Marcelo Quispe Lau Len
- Yaseem Stick Bañico Ramos

## Indice:
- [Ir a Tarea 1](#tarea-1)
- [Ir a Tarea 2](#tarea-2)
- [Ir a Tarea 3](#tarea-3)
---

## Tarea 1
Desarrollo de guías
### Guía 1 
- C++ : [Ver guía 1 en lenguaje C++](c++/guia1/ejercicios.md)
- Java: [Ver guía 1 en lenguaje Java](java/guia1/ejercicios.md)
- Diagramas de Flujo: [Ver guía 1 en diagramas de flujo](diagramasFlujo/guia1/ejercicios.md)


### Guía 2
- C++ : [Ver guía 2 en lenguaje C++](c++/guia2/ejercicios.md)
- Java: [Ver guía 2 en lenguaje Java](java/guia2/ejercicios.md)
- Diagramas de Flujo: [Ver guía 2 en diagramas de flujo](diagramasFlujo/guia2/ejercicios.md)

### Guía 3
- C++ : [Ver guía 3 en lenguaje C++](c++/guia3/ejercicios.md)
- Java: [Ver guía 3 en lenguaje Java](java/guia3/ejercicios.md)
- Diagramas de Flujo: [Ver guía 3 en diagramas de flujo](diagramasFlujo/guia3/ejercicios.md)

---
## Tarea 2
Función que imprima valor de cout (C++)
````
#include <iostream>

#include <string>

using namespace std;
/*Funcion para calcular la suma*/
int obtenerSuma(int num1, int num2)
{
    return num1 + num2;
}
int obtenerMultioplicacion (int num1,int num2)
{
    return num1 * num2;
}
/*Procedimiento para mostrar los resultados*/
void imprimir(string cadena)
{
    cout<<cadena<<endl;
}
void resultadosDelProblema (int suma, int multiplica)
{
    string suma_cadena = "La suma es " + to_string(suma);
    string multiplica_cadena= "La multiplicación es "+ to_string(multiplica);
    imprimir(suma_cadena);
    imprimir(multiplica_cadena);

}

int main()
{
    int numero1,numero2,suma,multiplica;
    cout<<"Digite un numero: ";
    cin>>numero1;
    cout<<"Digite otro numero: ";
    cin>>numero2;
    suma = obtenerSuma(numero1,numero2);
    multiplica = obtenerMultioplicacion(numero1,numero2);
    resultadosDelProblema(suma, multiplica);
}
````
---
## Tarea 3
Desarrollo de rutina en Haskell
````
import Data.List
import System. IO
-- para compilar el programa siempre digita :r
-- Data types 


-- Int
maxInt = maxBound :: Int
always5 :: Int


always5 = 5


--comentario
-- operaciones
addEx=5 + 4
subEx=5
mulEx = 5 * 4
divEx=5 / 4
{-
    commentario multilinea
-}

--residuo
modEx = mod 5 4

-- ciclo
listTimes2 [x*2 | x <- [1..10]] 
````

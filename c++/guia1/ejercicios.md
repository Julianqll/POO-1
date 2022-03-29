# Ejercicio 1
```c++
#include <iostream>

int main() {
    float base, altura, area, perimetro;
    std::cout << "------Area y perímetro de Rectángulo-----" << std::endl;
    std::cout << "Ingrese la base: ";
    std::cin >> base;
    std::cout << "Ingrese la altura: ";
    std::cin >> altura;
    area = base * altura;
    perimetro = 2*(base + altura);
    std::cout << "El área del rectángulo es: "<< area << std::endl;
    std::cout << "El perímetro del rectángulo es: " << perimetro << std::endl;
    return 0;
}
```
# Ejercicio2

```c++
#include <iostream>

int main() {
    float radio, altura, area_base, area_lateral, area_total, pi = 3.1416;
    std::cout << "------Area lateral, total y de la base de Cilindro-----" << std::endl;
    std::cout << "Ingrese el radio: ";
    std::cin >> radio;
    std::cout << "Ingrese la altura: ";
    std::cin >> altura;
    area_base =  pi * (radio * radio);
    area_lateral = 2 * pi * radio * altura;
    area_total = 2 * area_base + area_lateral;
    std::cout << "El área de la base del cilindro es: "<< area_base << std::endl;
    std::cout << "El área lateral del cilindro es: "<< area_lateral << std::endl;
    std::cout << "El área total del cilindro es: " << area_total << std::endl;
    return 0;
}
```
# Ejercicio 3

```c++
#include <iostream>

int main() {
    int edad;
    float peso, frecuencia;
    std::cout << "------Frecuencia cardiaca de un varón-----" << std::endl;
    std::cout << "Ingrese la edad(años): ";
    std::cin >> edad;
    std::cout << "Ingrese el peso(kg): ";
    std::cin >> peso;
    frecuencia = 210 - (0.5 * edad) - (0.01 * peso + 4);
    std::cout << "La frecuencia cardiaca es: "<< frecuencia << std::endl;
    return 0;
}
```

# Ejercicio 4

```c++
#include <iostream>

int main() {
    float peso, estatura, imc;
    std::cout << "------Indice de masa corporal (IMC)-----" << std::endl;
    std::cout << "Ingrese el peso(kg): ";
    std::cin >> peso;
    std::cout << "Ingrese la estatura(m): ";
    std::cin >> estatura;
    imc = peso / (estatura*estatura);
    std::cout << "El índice de masa corporal (IMC) es: "<< imc << std::endl;
    return 0;
}
```

# Ejercicio 5

```c++
#include <iostream>

int main() {
    float p1, p2, ep, ef, promedio;
    std::cout << "------Promedio final de alumno-----" << std::endl;
    std::cout << "Ingrese la nota de la primera práctica: ";
    std::cin >> p1;
    std::cout << "Ingrese la nota de la segunda práctica: ";
    std::cin >> p2;
    std::cout << "Ingrese la nota del examen parcial: ";
    std::cin >> ep;
    std::cout << "Ingrese la nota del examen final: ";
    std::cin >> ef;
    promedio = 0.1 * p1 + 0.1 * p2 + 0.35 * ep + 0.45 * ef;
    std::cout << "El promedio final del alumno es: "<< promedio << std::endl;
    return 0;
}
```

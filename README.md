# Reporte de Prácticas de Programación

## Carátula

| Dato | Información |
| --- | --- |
| Institución | Unidad Profesional Interdisciplinaria de Ingeniería y Ciencias Sociales y Administrativas |
| Asignatura | Abstracción y Uso de Datos |
| Periodo | Prácticas del primer parcial |
| Equipo  | Los Sin Oficio |
| Integrantes  | Cruz Montalvo Erick Itzmin|
|   | Murillo Sanchez Fatima Mariana|
|   | Pérez Rivera Leia Michelle|
| Docente | Yventz Entzana Garduño |
| Repositorio | https://github.com/LoSinOficio/1er_Departamental.git |


## Índice

1. [Desarrollo](#1-desarrollo)
2. [Solución de las prácticas y código esencial](#2-solución-de-las-prácticas-y-código-esencial)
3. [Compilación y ejecución](#3-compilación-y-ejecución)
4. [Conclusiones](#4-conclusiones)
5. [Referencias del repositorio](#5-referencias-del-repositorio)

## 1. Desarrollo

### Descripción del trabajo

Este repositorio reúne los programas elaborados para las prácticas de programación del primer parcial. Cada archivo `.cpp` contiene una práctica independiente que se puede consultar, compilar y ejecutar por separado. En conjunto, los ejercicios trabajan fundamentos de C++, programación estructurada y programación orientada a objetos.

### Objetivo

Aplicar los conceptos de programación vistos en clase mediante programas en C++, organizados por práctica y documentados para facilitar su revisión y ejecución.

### Fundamentación

Las prácticas progresan desde instrucciones, variables, operadores y entrada/salida hacia el uso de funciones y tipos compuestos. También incluyen clases y objetos, encapsulamiento y herencia, además del trabajo con arreglos, matrices y punteros. Los ejercicios complementarios exploran estructuras de datos y operaciones adicionales, incluyendo contenedores de la biblioteca estándar de C++.

Estos conceptos permiten dividir un problema en pasos, representar y procesar datos, y organizar el código en componentes con responsabilidades definidas. La programación orientada a objetos agrupa datos y operaciones relacionadas en clases; las estructuras de datos permiten almacenar colecciones y aplicar operaciones como insertar, buscar o eliminar elementos.

### Procedimiento

1. Se identificó el tema o requerimiento de cada ejercicio.
2. Se seleccionaron las variables, estructuras de control o clases necesarias para representar la solución.
3. Se implementó cada ejercicio en un archivo C++ independiente, con una función `main` que inicia el programa.
4. En los programas interactivos, se reciben datos mediante la consola y se procesan de acuerdo con las opciones o reglas de cada práctica.
5. Cada archivo se puede compilar y ejecutar por separado para observar su comportamiento y revisar la solución.

### Temas trabajados

- Variables, operadores, expresiones y entrada/salida.
- Funciones y organización del programa.
- Clases, objetos y programación orientada a objetos.
- Arreglos, matrices, punteros y tipos compuestos.
- Estructuras de datos y operaciones con bits.
- Contenedores de la biblioteca estándar de C++ (STL).

## 2. Solución de las prácticas y código esencial

La solución de cada ejercicio se encuentra en el archivo enlazado en las tablas de referencia. La clasificación y descripción siguen la tabla de prácticas compartida; la última columna conserva el valor de POO indicado en esa referencia. A continuación se presenta un ejemplo básico del repositorio para ilustrar la creación y uso de un objeto.

### Ejemplo 1: clase y objeto

En [Practica 01.cpp](./Practica%2001.cpp) se define una clase con un método y se invoca ese método desde un objeto:

```cpp
class Mensaje {
public:
	void saludar() {
		cout << "Hola mundo" << endl;
	}
};

int main() {
	Mensaje miObjeto;
	miObjeto.saludar();
	return 0;
}
```

La clase `Mensaje` reúne el comportamiento `saludar`; `main` crea `miObjeto` y utiliza el operador punto para llamar al método. Al ejecutar el programa, se muestra `Hola mundo`.

### Matriz de prácticas: primer parcial

| Ejercicio | Concepto general | Práctica / solución | POO |
| --- | --- | --- | ---: |
| 1 | Fundamentos de programación | Hola mundo: [Practica 01.cpp](./Practica%2001.cpp) | 1 |
| 2 | Fundamentos de programación | Suma de dos números recibidos como parámetros: [Practica 02.cpp](./Practica%2002.cpp) | 1 |
| 3 | Fundamentos de programación | Calculadora básica con suma, resta, multiplicación y división: [Practica 03.cpp](./Practica%2003.cpp) | 1 |
| 4 | Sobrecarga | Calculadora con variantes de funciones que reciben dos, cero o tres parámetros: [Practica 04.cpp](./Practica%2004.cpp) | 1 |
| 5 | Herencia | Crear una calculadora derivada a partir de la anterior: [Practica 05.cpp](./Practica%2005.cpp) | 1 |
| 6 | Herencia y sobrescritura | Extender la calculadora y sobrescribir operaciones; incluir multiplicación sucesiva, potencia y división mediante restas: [Practica 06.cpp](./Practica%2006.cpp) | 1 |
| 7 | Creación de tipos de datos | Definir `Auto` y `Persona` en programación estructurada y orientada a objetos: [Practica 07.cpp](./Practica%2007.cpp), [Practica 07 POO.cpp](./Practica%2007%20POO.cpp) | 1 |
| 7 bis | Tamaño de tipos | Identificar el tamaño de tipos básicos y de tipos creados: [Practica 07.1.cpp](./Practica%2007.1.cpp) | 1 |
| 8 | Promedio | Procesar cinco números y obtener promedio, media, máximo, mínimo y suma: [Practica 08 POO.cpp](./Practica%2008%20POO.cpp) | 1 |
| 9 | Promedio con arreglo | Calcular estadísticas de cinco valores almacenados en un arreglo: [Practica 09.cpp](./Practica%2009.cpp) | 1 |
| 10 | Promedio con puntero al arreglo | Acceder indirectamente a cinco valores y calcular sus estadísticas: [Practica 10.cpp](./Practica%2010.cpp) | 1 |
| 11 | Matrices | Operar con matrices: producto por una constante y multiplicación de matrices: [Practica 11.cpp](./Practica%2011.cpp) | 1 |
| 12 | Tipo de dato con arreglo | Crear una colección de personas y autos usando los tipos del ejercicio 7: [Practica 12.cpp](./Practica%2012.cpp) | 1 |
| 13 | Tipo de dato con puntero al arreglo | Acceder indirectamente a los elementos de la colección de personas: [Practica 13.cpp](./Practica%2013.cpp) | 1 |
| 14 | Recursividad | Resolver factorial, Fibonacci y operaciones sucesivas de la calculadora mediante recursión: [Practica 14.cpp](./Practica%2014.cpp) | 1 |
| 15 | Recursividad y fractales | Generar fractales como el triángulo de Sierpinski y el polvo de Cantor: [Practica 15.cpp](./Practica%2015.cpp) | 1 |

## 3. Compilación y ejecución

Se requiere un compilador compatible con C++11 o posterior, como `g++`. Desde la carpeta del repositorio, compila un archivo a la vez:

```bash
g++ -std=c++11 "Practica 01.cpp" -o practica1
```

En Windows, ejecuta el programa compilado con:

```powershell
.\practica1.exe
```

En Linux o macOS:

```bash
./practica1
```

Para probar otra práctica, reemplaza el nombre del archivo fuente y el nombre del ejecutable. Cada archivo tiene su propio `main`, por lo que las prácticas deben compilarse de forma independiente.

## 4. Conclusiones

El conjunto de prácticas ofrece una aplicación gradual de conceptos de C++: desde instrucciones y funciones hasta clases, colecciones y estructuras de datos. Mantener cada ejercicio en un archivo separado permite estudiar las soluciones individualmente y ejecutar ejemplos sin mezclar sus puntos de entrada.

## 5. Referencias del repositorio

- Código fuente y soluciones: archivos `.cpp` enlazados en el índice de soluciones.
- Biblioteca estándar de C++ utilizada por algunas prácticas: encabezados como `<iostream>`, `<string>`, `<list>` y `<algorithm>`.


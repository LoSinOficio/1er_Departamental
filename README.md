# Reporte de Prácticas de Programación

## 1. Carátula

| Dato | Información |
| --- | --- |
| Institución | [Nombre de la institución] |
| Asignatura | Programación |
| Trabajo | Prácticas de programación en C++ |
| Periodo | Primer parcial |
| Estudiante | [Nombre del estudiante] |
| Docente | [Nombre del docente] |
| Fecha de entrega | [Día/mes/año] |
| Repositorio | [Enlace al repositorio de GitHub] |

> Completa los campos entre corchetes antes de entregar el reporte.

## 2. Índice

1. [Carátula](#1-carátula)
2. [Índice](#2-índice)
3. [Desarrollo](#3-desarrollo)
4. [Solución de las prácticas y código esencial](#4-solución-de-las-prácticas-y-código-esencial)
5. [Compilación y ejecución](#5-compilación-y-ejecución)
6. [Conclusiones](#6-conclusiones)
7. [Referencias del repositorio](#7-referencias-del-repositorio)

## 3. Desarrollo

### Descripción del trabajo

Este repositorio reúne los programas elaborados durante el primer parcial de la asignatura de Programación. Cada archivo `.cpp` contiene una práctica independiente que se puede consultar, compilar y ejecutar por separado. En conjunto, los ejercicios trabajan fundamentos de C++, programación estructurada y programación orientada a objetos.

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

## 4. Solución de las prácticas y código esencial

La solución de cada ejercicio se encuentra en el archivo enlazado en el índice de prácticas. Los siguientes fragmentos muestran dos ideas implementadas en este repositorio: la creación y uso de un objeto, y la inserción de elementos en una lista de la STL.

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

### Ejemplo 2: lista dinámica con STL

En [Practica 22_10.cpp](./Practica%2022_10.cpp) se utiliza `std::list<int>` para almacenar enteros y se encapsulan las operaciones de inserción en métodos:

```cpp
class ListaDinamicaSTL {
private:
	list<int> elementos;

public:
	void agregarAlFinal(int valor) {
		elementos.push_back(valor);
	}

	void agregarAlFrente(int valor) {
		elementos.push_front(valor);
	}
};
```

La lista administra dinámicamente sus elementos. `push_back` agrega al final y `push_front` al inicio; la práctica completa también incluye búsqueda, eliminación, visualización y un menú de consola.

### Índice de soluciones

#### Prácticas 01 a 08: fundamentos y POO

- [Practica 01.cpp](./Practica%2001.cpp)
- [Practica 02.cpp](./Practica%2002.cpp)
- [Practica 03.cpp](./Practica%2003.cpp)
- [Practica 04.cpp](./Practica%2004.cpp)
- [Practica 05.cpp](./Practica%2005.cpp)
- [Practica 06.cpp](./Practica%2006.cpp)
- [Practica 07.cpp](./Practica%2007.cpp)
- [Practica 07.1.cpp](./Practica%2007.1.cpp)
- [Practica 07 POO.cpp](./Practica%2007%20POO.cpp)
- [Practica 08 POO.cpp](./Practica%2008%20POO.cpp)

#### Prácticas 09 a 21: estructuras y procesamiento de datos

- [Practica 09.cpp](./Practica%2009.cpp)
- [Practica 10.cpp](./Practica%2010.cpp)
- [Practica 11.cpp](./Practica%2011.cpp)
- [Practica 12.cpp](./Practica%2012.cpp)
- [Practica 13.cpp](./Practica%2013.cpp)
- [Practica 14.cpp](./Practica%2014.cpp)
- [Practica 15.cpp](./Practica%2015.cpp)
- [Practica 16.cpp](./Practica%2016.cpp)
- [Practica 17.cpp](./Practica%2017.cpp)
- [Practica 18.cpp](./Practica%2018.cpp)
- [Practica 19.cpp](./Practica%2019.cpp)
- [Practica 20.cpp](./Practica%2020.cpp)
- [Practica 21.cpp](./Practica%2021.cpp)

#### Prácticas complementarias 22

- [Practica 22_01.cpp](./Practica%2022_01.cpp)
- [Practica 22_02.cpp](./Practica%2022_02.cpp)
- [Practica 22_03.cpp](./Practica%2022_03.cpp)
- [Practica 22_04.cpp](./Practica%2022_04.cpp)
- [Practica 22_05.cpp](./Practica%2022_05.cpp)
- [Practica 22_06.cpp](./Practica%2022_06.cpp)
- [Practica 22_07.cpp](./Practica%2022_07.cpp)
- [Practica 22_07bits.cpp](./Practica%2022_07bits.cpp)
- [Practica 22_08.cpp](./Practica%2022_08.cpp)
- [Practica 22_09.cpp](./Practica%2022_09.cpp)
- [Practica 22_10.cpp](./Practica%2022_10.cpp)

## 5. Compilación y ejecución

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

## 6. Conclusiones

El conjunto de prácticas ofrece una aplicación gradual de conceptos de C++: desde instrucciones y funciones hasta clases, colecciones y estructuras de datos. Mantener cada ejercicio en un archivo separado permite estudiar las soluciones individualmente y ejecutar ejemplos sin mezclar sus puntos de entrada.

## 7. Referencias del repositorio

- Código fuente y soluciones: archivos `.cpp` enlazados en el índice de soluciones.
- Biblioteca estándar de C++ utilizada por algunas prácticas: encabezados como `<iostream>`, `<string>`, `<list>` y `<algorithm>`.


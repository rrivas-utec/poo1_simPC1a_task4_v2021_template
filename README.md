# Task #4: Simulación PC1  
**course:** Programación Orientada a Objetos I  
**unit:** Unidad 1 y Unidad 2 
**cmake project:** poo1_simPC1a_task4_v2021
## Indicaciones Especificas
- El tiempo límite para la evaluación es 100 minutos.
- Cada pregunta deberá ser respondida en un archivo fuente (`.cpp`) y un archivo cabecera (`.h`) con el número de la pregunta:
    - `p1.cpp, p1.h`
    - `p2.cpp, p2.h`
    - `p3.cpp, p3.h`
- Deberás subir estos archivos directamente a [www.gradescope.com](https://www.gradescope.com) o se puede crear un `.zip` que contenga todos ellos y subirlo.

## Competencias
- Para los alumnos de la carrera de Ciencia de la Computación
    - Aplicar conocimientos de computación y de matemáticas apropiadas para la disciplina. **(Evaluar)**
    - Analizar problemas e identificar y definir los requerimientos computacionales apropiados para su solución. **(Usar)**
    - Utilizar técnicas y herramientas actuales necesarias para la práctica de la computación. **(Usar)**

- Para los alumnos de las carreras de Ingeniería
    - Capacidad de aplicar conocimientos de matemáticas **(nivel 3)**
    - Capacidad de aplicar conocimientos de ingeniería **(nivel 2)**
    - Capacidad para diseñar un sistema, un componente o un proceso para satisfacer las necesidades deseadas dentro de restricciones realistas. **(nivel 2)**

## Question #1 - El producto palindrome (7 ptos)

Un número palindrome es aquel que leído al revés da el mismo número ejemplo 1001. 
Escribir un programa que lea un valor que represente la cantidad **`d`** de dígitos de un número y que calcule el mayor número palindrome formado por la multiplicación de 2 números de **`d`** dígitos. 

#### Input Format

```cpp
2
```

#### Constraints

```cpp
No utilizar etiquetas
```

#### Output Format

```cpp
91
99
```
#### Ejemplo 1
**Input**
```cpp
5
```
**Output**
```cpp
```

#### Ejemplo 1
**Input**
```cpp
3
```
**Output**
```cpp
913
993
```

#### Ejemplo 2
**Input**
```cpp
4
```
**Output**
```cpp
9901
9999
```

## Question #2 - Suma de dígitos de potencia (7 points)

Escribir una función que permita calcular la suma de los dígitos de un número entero elevado a una potencia entera positiva, el programa debe leer 2 números pasárselos a la función como parámetros, calcular dentro de la función la potencia de esos números y luego calcular la suma de los dígitos y retornar el valor usando el tipo de datos de retorno.

#### Input Format

```cpp
2
4
```

#### Constraints

```cpp
No utilizar etiquetas
```

#### Output Format

```cpp
7
```
#### Ejemplo 1
**Input**
```cpp
11
13
```
**Output**
```cpp
47
```

#### Ejemplo 2
**Input**
```cpp
7
11
```
**Output**
```cpp
49
```

## Question #3 - Invertir un String de forma recursiva (6 points)

Escribir una función recursiva cuyo nombre es `invertir_texto` que reciba 1 parámetro del tipo `std::string` y que permite invertirlo y que retornar por medio del tipo de retorno de la función el texto invertido.

#### Input Format

```cpp
Hola Mundo 
```

#### Constraints

```cpp
No utilizar etiquetas
```

#### Output Format

```cpp
odnuM aloH
```
#### Ejemplo 1
**Input**
```cpp
Invirtiendo un texto
```
**Output**
```cpp
otxet nu odneitrivnI
```

## Question #3b - Convertir un número texto binario en otro - BONUS

Escribir una función cuyo nombre es `convertir_texto_binario` que reciba 2 parámetros del tipo `std::string` y que permite retornar por medio del tipo de retorno de la función el número mínimo de intercambios de modo que el primer texto binario sea igual al segundo texto binario.

#### Input Format

```cpp
1100
1001
```

#### Constraints

```
1. No utilizar etiquetas
2. Los 2 parametros de la funcion deben ser del tipo std::string
3. Los 2 parametros deben ser del mismo tamaño
4. Los 2 parametros deben tener los mismos digito en diferente orden o el mismo
3. Los intercambios entre dos caracteres no necesariamente deben ser caracteres continuos
```

#### Output Format

```cpp
1   // Se hizo solo 1 intercambio entre: 2do - 4to
```
#### Ejemplo 1
**Input**
```cpp
110011
010111
```
**Output**
```cpp
1   // Se hizo un solo intercambio entre: 1ero - 4to
```
#### Ejemplo 2
**Input**
```cpp
10011001
01100110
```
**Output**
```cpp
4   // Se hizo 4 intercambios entre: 1ero - 2do, 3ro - 4to, 5to - 6to y 7mo - 8vo 
```

#### Ejemplo 3
**Input**
```cpp
110011000111
010111101010
```
**Output**
```cpp
3   // Se hizo 3 intercambios entre: 1ero - 4to, 7mo - 10mo, 9no - 12vo
```



# Documentación del Proyecto

## Índice

1. [Introducción](#1-introducción)
2. [Instalación](#2-instalación)
3. [Uso](#3-Uso)
4. [Uso](#4-uso)
5. [Ejemplos](#5-ejemplos)
6. [Contribución](#6-contribución)
7. [Licencia](#7-licencia)

## 1. Introducción ¿Cómo funciona Clipper?

¿Cómo funciona Clipper?
1. Lenguaje de Programación:

Clipper es un lenguaje de programación procedural diseñado principalmente para el desarrollo de aplicaciones de bases de datos.
Se utiliza para crear aplicaciones de software que interactúan con bases de datos de xBase, como dBASE o FoxPro.

2. Características Principales:

Procedural: Clipper sigue un enfoque procedural en la programación, similar a otros lenguajes de esa época.

Manejo de Bases de Datos: Es conocido por su capacidad para interactuar con bases de datos de forma eficiente.

Sintaxis Simple: La sintaxis de Clipper es relativamente simple y directa.

3. Desarrollo de Aplicaciones:

En Clipper, desarrollas aplicaciones mediante la creación de programas que interactúan con bases de datos y realizan operaciones específicas.

4. Estructura de Programas:

Los programas en Clipper consisten en módulos que contienen código fuente. Estos módulos pueden incluir funciones, procedimientos y llamadas a otras partes del programa.

5. Bibliotecas y Compilación:

Clipper utiliza bibliotecas de funciones que puedes incluir en tus programas para facilitar tareas comunes.
Los programas Clipper se compilan antes de ejecutarse, y el código fuente se transforma en un formato ejecutable.

## 2. Instalación

Para visualizar los archivos, editarlos y compilarlos es necesario instalar una extencion para VSCode llamada Harbour and xHarbour

![Harbour and xHarbour](files/image.png)

Para aprender más sobre como usar la extención de Harbour ir a [Harbour and xHarbour](https://medium.com/harbour-magazine/visual-studio-code-para-harbour-85b0646ff312)

```bash
# Ejemplo de comandos de instalación
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
# Comandos adicionales de instalación si es necesario
```
## 3. Uso
A continuacion se muestran ejemplos de usos basicos en clipper 

1. Hello World en Clipper:
```Bash
PROCEDURE Main
   ? "Hello, World!"
   RETURN
```
2. Declaración de Variables y Estructura de Control:
```Bash
PROCEDURE Main
   LOCAL nNumero := 5

   IF nNumero > 0
      ? "El número es positivo."
   ELSE
      ? "El número es cero o negativo."
   ENDIF

   RETURN
```




## 4.

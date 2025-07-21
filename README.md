# Taller-guiado

# Trabajando con Cadenas de Caracteres en Python

Este repositorio contiene una serie de ejercicios prácticos para aprender y practicar el manejo de CADENAS DE CARACTERES(strings) en Python. Cada ejercicio incluye una descripción dando la instrucción a seguir, una guía y un código base.


# Ejercicio 1: Contando caracteres
Objetivo:  
Contar el total de caracteres y la cantidad de espacios en una frase ingresada por el usuario.

- Uso de `len()` para contar caracteres.
- Uso de `.count(" ")` para contar espacios.

# Ejercicio 2: Validando nombres
Objetivo: 
Verificar si un nombre ingresado por el usuario:

1. Solo contiene letras.
2. Comienza con mayúsculas (en cada palabra).

- Uso de `.isalpha()` después de eliminar espacios.
- Uso de `.istitle()` para validar mayúsculas.

# Ejercicio 3: Invirtiendo palabras
Objetivo: 
Mostrar la palabra ingresada por el usuario, pero al revés.

- Uso de slicing `[::-1]` para invertir cadenas.

# Ejercicio 4: Cifrando texto
Objetivo: 
Reemplazar todas las vocales (mayúsculas y minúsculas) de una frase por el carácter `*`.

- Uso repetido de `.replace()` para reemplazar cada vocal.

# Ejercicio 5: Contador de vocales
Objetivo: 
Contar cuántas vocales (mayúsculas y minúsculas) hay en una frase ingresada por el usuario.

- Uso de `.count()` para cada vocal.
- Suma total de todas las vocales.

# Ejercicio 6: Formateando cadenas
Objetivo:  
Formatear un número de teléfono de 10 dígitos como: `(XXX) XXX-XXXX`.

- Validación de longitud y uso de `.isdigit()`.
- Uso de slicing y f-strings para el formato.

# Ejercicio 7: Detectando palíndromos
Objetivo:  
Determinar si una palabra es un **palíndromo**, es decir, que se lee igual al derecho y al revés.

- Conversión a minúsculas con `.lower()`.
- Comparación entre la cadena original y su versión invertida.

# Ejecución

Puedes ejecutar cada archivo por separado desde la terminal o cualquier entorno de desarrollo. También puedes agruparlos en un solo archivo `.py` para explorarlos uno a uno.


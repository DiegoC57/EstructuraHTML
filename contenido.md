1. ¿Qué es Python?
Es un lenguaje de programación sencillo, creado por Guido van Rossum. Se usa para páginas web, juegos y análisis de datos debido a su sintaxis corta y fácil de leer.

2. Instalación
Descargar desde https://www.python.org.

Verificar en la terminal con: python --version

Recomendado usar Visual Studio Code.

3. Variables y Tipos de Datos
En Python las variables no requieren declarar su tipo explícitamente:

nombre = "Pedro"  # str (texto)
edad = 19         # int (entero)
precio = 3.5      # float (decimal)
activo = True     # bool (booleano)

4. Operadores
Aritméticos: + (suma), - (resta), * (multiplicación), / (división)

Comparación: == (igual), > (mayor que), < (menor que)

5. Condicionales
Toman decisiones según una condición:

edad = 19
if edad >= 18:
print("Mayor de edad")
else:
print("Menor de edad")

6. Bucles
Repiten bloques de código:

Bucle for
for i in range(5):
print(i)

Bucle while
contador = 0
while contador < 3:
print("Hola")
contador += 1

7. Listas
Guardan múltiples elementos ordenados:

frutas = ["manzana", "banana", "uva"]
print(frutas[0])       # Acceder al primer elemento
frutas.append("pera")  # Agregar un elemento

8. Funciones
Bloques de código reutilizables:

def saludar(nombre):
print("Hola " + nombre)

saludar("Pedro")
# PYTHON _(Para principiantes):_

### VARIABLES:


_<p>Hay varios tipos de variables:</p>_

- int
- float
- complex
- str
- bool
- list
- tuple
- set
- dict

``` Python
#Ejemplos        

enteros = 10 #int

decimales = 10.0 #float

numeros_complejos = 4j #complex

saludo = "Hola mundo" #str

es_capicua = False #bool

array_de_numeros = [1, 2, 3, 4, 3, 4] #list

tupla_de_datos = ("Ana", 25, True) #tuple

set_de_datos = {1, 2, 3, 4} #set

diccionario_ana = { #dict
    "nombre": "Ana",
    "edad": 23,
    "es_estudiante": True
}
```

### OUTPUT:

_<p>El output es la forma en la que el programa le muestra información al usuario.
La herramienta principal para esto es la función print().</p>_

```Python
# La forma básica de mostras cosas por pantalla es mediante:

print () #<- este print imprime una línea en blanco, porque el () está vacío. 

# Se puede mostrar cualquier cosa: mensajes, variables...
# por ejemplo:
```
---

```Python
# variables

variable_numero_entero = 10
print (variable_numero_entero)
```

```console
Salida por consola:
10
```
---
```Python
# mensajes
print ("Hola, Mundo!")
```

```console
Salida por consola:
Hola, Mundo!
```
---
<br>

### PRINT + VARIABLES:
_Con lo que llevamos aprendido ya podemos empezar a jugar. Llamar a variables, hacer cálculos matemático, o incluso concatenar._

#### _Suma:_

```Python
print (5+10)
```
```Console
Salida por consola:
15
```
#### _Resta:_
```Python
print (10-5)
```
```Console
Salida por consola:
5
```
#### _Multiplicación:_
```Python
print (5*10)
```
```Console
Salida por consola:
50
```
#### _División:_
```Python
print (10/5) #Nota: la división no devuelve un número entero, a menos que pongamos doble /.
```
```Console
Salida por consola:
2.0 
```
#### _Operaciones complejas:_
```Python
print (((5+10)*10)/20)
```
```Console
Salida por consola:
7.5
```

_Como ya dijimos, se puede concatenar valores, pare eso usamos el "+" y para separar valores, la "," ._

```Python
# Ejemplos de concatenación:

concursante = "Juan"
saludo = "Hola " + concursante

print (saludo)
```


```Console
Salida por consola:
Hola Juan
```

```Python
concursante = "Juan"
edad = 25

print(concursante, edad)
```

```Console
Salida por consola:
Juan 25
```

### INPUT:

<p>El input permite que el usuario introduzca datos por teclado mientras el programa se está ejecutando.
En Python se usa la función <code>input()</code>.</p>

```Python
nombre = input("Introduzca su nombre: ")
print (nombre)
```
```Console
Salida por consola:
Introduzca su nombre: Nicolás 

Nicolás <--- Saca el valor introducido mediante el print.

```
 <br>

 # - Ejercicio 1.

**Definición de variables:** _Define una variable de tipo <code>str</code> para el nombre de un proyecto y variables de tipo <code>float</code> para representar un ***"presupuesto inicial"*** y un ***"gasto garantizado"***_ .

**Uso del input:** _Utiliza el <code>input</code> para que el usuario introduzca los valores de cada variable._

**Operaciones matemáticas:** 
- _Calcula el ***"Saldo Restante"*** realizando una resta entre el presupuesto y el gasto._
- _Calcula un ***"Impuesto proyectado"*** (por ejemplo, el 15%) aplicando una multiplicación al gasto realizado._

**Output de resultados:** Utiliza la función <code>Print()</code>



- _Usa la "," para separar diferentes valores dentro de un mismo print._














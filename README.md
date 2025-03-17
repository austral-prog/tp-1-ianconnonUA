[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/nYqVF7Kz)
# Trabajo Práctico 1

## Ejercicio 1

Para este ejercicio el objetivo es leer el código, anotar lo que piensen que los prints vayan a decir y luego correr el código para ver si les dio igual o no.

```python
i1 = 3 # se define una variable llamada i1 de tipo entero
i2 = 5 # se define una variable llamada i2 de tipo entero
i3 = i2 + i1 # se define una variable llamada i3 que es la suma de i2 e i1
print("valor de i1:") # imprime el texto "valor de i1:"
print(i1) # imprime el valor de i1 -> 3
print("valor de i2:") # imprime el texto "valor de i2:"
print(i2) # imprime el valor de i2 -> 5
print("valor de i3:") # imprime el texto "valor de i3:"
print(i3) # imprime el valor de que se encuentra en la variable i3 -> suma de i2 e i1
print(i1 + i2 + i3) # imprime la suma de i1, i2 e i3

s1, s2, s3 = "Python", " is ", 'awesome' # se definen tres variables de tipo string
print(s1 + s2 + s3)  # se muestra el contenido de las tres variables concatenadas

x = y = z = "Naranja" # se definen tres variables de tipo string con el mismo valor
print("valor de x: " + x + ", valor de y: " + y + ", valor de z: " + z) # se imprime el valor de las tres variables concatenadas, con un texto que las identifica (valor de x, valor de y, valor de z)

z1 = i3 / i2 # se define una variable z1 que es el resultado de la división de i3 por i2
print(z1) # se imprime el valor de z1
z2 = i3 % i2 # se define una variable z2 que es el resto de la división de i3 por i2
print(z2)   # se imprime el valor de z2
f1 = -.5 # se define la variable f1 que tiene un valor de -0.5 de tipo float
f2 = 10 # se define la variable f2 que tiene un valor de 10 de tipo float
f3 = f1 + f2 # se define la variable f3 que es la suma de f1 y f2
i3 = int(f3) # se define la variable i3 que es la parte entera de f3
print("entero i3:") # se imprime "entero i3:"
print(i3)  # se imprime el valor de i3
print("variable f3:") # se imprime "variable f3:"
print(f3)   # se imprime el valor de f3
f2 += i1 # se le concatena a f2 el valor de i1
print("el valor de") # se imprime "el valor de"
print(f2)  # se imprime el valor de f2
print("más") # se imprime la frase "más"
print(f1)  # se imprime el valor de f1
print("es:") # se imprime el texto "es:"
print(f2 + f1) # se imprime la suma de f2 y f1

# Al ejecutar el codigo en la consola de comandos los resultados fueron iguales a los esperados

```

## Ejercicio 2 - Math

Escribir un programa dentro de exercise_math.py que dado dos números enteros imprima en pantalla el resultado de las siguientes operaciones: la suma, la diferencia, el producto, el promedio, el cociente entero y el resto de la división entera y el valor real de la división. Para entregar correctamente se deberá imprimir dichos resultados en el orden que fueron pedidos en la consigna. Por ejemplo, primero la suma, despues la diferencia, y asi sucesivamente.

Ejemplo: Para a = 57 y b = 7 el output debera ser:

```python
64
50
399
32.0
8
1
8.142857142857142
```



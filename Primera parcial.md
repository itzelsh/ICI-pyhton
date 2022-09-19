# Primera Parcial: Avanzados en programación 
## Problemas resueltos en clase  con el lenguaje Python
###  Ejercicio 1. Imprimir un mensaje y un nombre 
#### 1.1 Descripción del problema 
Escribir una función  que reciba un mensaje y un nombre 
y escriba en pantalla  "___mensaje nombre___"
#### 1.2 Código 
```  python
def mensaje (msg:str, nom:str)->str:
return f"{msg} {nom}"
```
#### 1.3 Implementación 
``` python 
print (mensaje("Buen día", "Carmen"))
```
#### 1.4 Salida 
```
Buen día Carmen
```
###  Ejercicio 2. Imprimir  
####  2.1 Descripción del problema
Escribir 2 números por pantalla y mostramos 2 resultados, la suma y el cuadrado que vienen dados por
dos funciones del mismo nombre
####  2.2 Código
``` python
def cuadrado(n: int)->int|float: return n*n
def suma(a:int|str,b:int|str)->int|str: return a+b
```
### 2.3 Implementacion
``` python
imprimir(suma(1, 1))
print(suma("Hola", "mundo"))
print(suma(1, "hola"))
imprimir(cuadrado(2))
```
#### Salida 1.4
```
hola mundo
Hola
```
###  Ejercicio 3. Imprimir  
####  2.1 Descripción del problema
Escribir el año de nacimiento y el año actual retornando el mensaje
####  2.2 Código
``` python
def calcular_edad(a_nacimiento:int, a_actual:int) -> int:
    return a_actual - a_nacimiento
def mensaje3(name:str, a_nacimiento:int, a_actual:int) -> str:
return f"hola {name} tienes {calcular_edad(a_nacimiento, a_actual)}"
```
### 2.3 Implementacion
``` python
x = print(" Introduzca su nombre ")
nombre = str(input())
y = print("Introduzca su año de nacimiento ")
año = int(input())
calculo = 2022 - año
print("Hola ", nombre ," su edad desde" ,año, "es de",  calculo, )
```
#### Salida 1.4
```
2003 y 2022
```
###  Ejercicio 4. Imprimir  
####  2.1 Descripción del problema
Escribe  operaciones basicas de matematicas suma,resta,división y multiplicación y las exporta 
####  2.2 Código
``` python
def sumar(a: int|float,b: int|float)->int|float:
    return a+b
def cuadrado(a: int|float,b: int|float)->int|float:
    return a*a
def restar(a: int|float,b: int|float)->int|float:
    return a-b
def multiplicar(a: int|float,b: int|float)->int|float:
    return a*b
def dividir(a: int|float,b: int|float)->int|float:
    return a/b
```
### 2.3 Implementacion
``` python
if __name__ == "__main__":
    print(op.sumar(5,5))
    print(op.restar(6,10))
    print(op.multiplicar(6,18))
    print(op.dividir(6,10))
    print(op.cuadrado(6))
```
#### Salida 1.4
```
2+3=5
2-2=0
5*5=25
10/2=5
2*2=4
```
###  Ejercicio 5. Imprimir  
####  2.1 Descripción del problema
Escribir listas en diferentes maneras
####  2.2 Código
``` python
lista1=[0,1,2,3,4]
lista2=[5,6,7]
lista1[len(lista1):]=lista2
lista1.extend(lista2)
lista1.append(lista2)
```
### 2.3 Implementacion
``` python
print(lista1)
```
#### Salida 1.4
```
[0,1,2,3,4] [5,6,7]
```



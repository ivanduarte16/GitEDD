
### Calc.c
Aquí estaran las funciones implementadas

### Calc.h
Este fichero contendrá las cabeceras de las funciones del fichero calc.c

### Calcula.c
Este contiene el main del programa

### Makefile
En este fichero le indicaremos al programa Make que ha de hacer para compilar

### Compilacion

#### 1 Manera
Ir al terminal e introducir la orden: make Calcula

#### 2 Manera

```
gcc -g -wall -c calc.c -o calc.o 

-Wall -g calcula.c calcula.o -o calcula
```
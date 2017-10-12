# TARJETA DE CRÉDITO VÁLIDA


En este ejercicio se debe ingresar número de una tarjeta de crédito y confirmar su validez según el algoritmo de Luhn.


### Pseudocódigo 
~~~
	Leer número de tarjeta 
	Validar que lo ingresasdo es número, no es vacío y sea de 13 dígitos
	Pasar los números a un array en orden inverso
	Multiplicar por 2 los números en posiciones pares
	Si el resultado de la multiplicación es mayor o igual a 10 se suma digitos del resultado
	Sumar todos los números (en posiciones pares e impares)
	Sacar el módulo de 10 
	Si el resultado es 0 es tarjeta válida
	Caso contrario tarjeta inválida
~~~
### Diagrama de flujo

![Imagen de diagrama](/assets/docs/diagrama.jpg)
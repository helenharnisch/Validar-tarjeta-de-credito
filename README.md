# Tarjeta de crédito válida

## Crea una web que pida, por medio de un prompt(), el número de una tarjeta de crédito
y confirme su validez según el algoritmo de Luhn.

#### function isValidCard por medio de un do while, pregunto al usuario por los numeros de su tarjeta
que debe ingresar.
Este buclé obligará a introducir un numero.
Preguntará una y otra vez hasta que obtenga algo que no sea una cadena vacía.
Al aplicar el operador ! convierte un valor a Boolean negándolo.
Esto significa que el bucle continúa corriendo hasta que des un numero que no sea una cadena vacía.

Para confirmar su validez por medio del algoritmo de Luhn.

Debemos pasar los numeros de la tarjeta a un array vacío, donde los devolvera de forma inversa.
Para invertir un array se usa .reverse(), pero nunca encontre la forma de poder ejecutar bien
este for.

Aplicar la operación a los numeros de las posiciones pares.

Los numeros de las posiciones pares se debe multiplicar por 2 y si es el doble de ese numero es mayor
mayor o igual a 10 debemos sumar los digitos del resultado.

Sumar los digitos de las posiciones impares y el nuevo numero que se obtiene de las posiciones pares.
Ese se deben sumar todos los resultados y deberas obtener el residuo de la división entre 10 y si es
igual a 0 significa que es una tarjeta de credito valida.

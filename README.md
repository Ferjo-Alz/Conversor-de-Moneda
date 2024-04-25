# Conversor-de-Moneda
 Practicando con Java: Challenge Conversor de Monedas
 
1.Definición de las tasas de cambio: Al principio del código, definimos un objeto llamado tasasDeCambio. Este objeto contiene pares de claves y valores que representan las tasas de cambio entre diferentes monedas. Por ejemplo, la clave "USD_ARS" tiene un valor de 873, lo que significa que 1 dólar estadounidense equivale a 873 pesos argentinos.

2.Función convertirMoneda: Esta función toma un monto y una tasa de cambio como argumentos. Multiplica el monto por la tasa de cambio correspondiente en el objeto tasasDeCambio para obtener el monto convertido.

3.Función menu: Esta función muestra un menú al usuario con diferentes opciones de conversión de moneda. El usuario puede seleccionar una opción ingresando un número. Luego, la función solicita al usuario que ingrese un monto para convertir.

4.Conversión de moneda: Dependiendo de la opción que elija el usuario, la función menu llama a la función convertirMoneda con el monto ingresado por el usuario y la tasa de cambio correspondiente. Luego, muestra el   resultado de la conversión al usuario.

5.Salir del programa: Si el usuario selecciona la opción 7, el programa se cierra.

6.Opción inválida: Si el usuario ingresa una opción que no está en el menú, el programa muestra un mensaje de error.

7.Finalmente, el código llama a la función menu para iniciar el programa.

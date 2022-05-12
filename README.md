# CALCULADORA BASICA MENU

Una calculaadora basica se puede realizar con condiciones.  se desea relizar de las operaciones basicas con dos numeros `x, y` .  Ademas se desea calcular la potencia y el logaritmo. se deben de considerar los casos donde `y =0` donde la division `x/y`NO se puede realizar y cuando `x<= 0` donde NO se puede calcular el `log(x)` . se desea generar un menu para el usuario pueda seleccionar la operacion a realizar. una manera de hacerlo es la siguiente:

1. se reciben los dos numeros `x, y` para realizarla operacion.
2. se recibe la operacion a realizar mediante la variable `opcion`la que selecciona en el menu que operacion ejecuta el agoritmo.
3.se inicializa la variable logica `bandera - false `. si la division o el logaritmo no se pueden calcular, se hace `bandera = true`.
4. mediante condiciones se realiza la operacion deseada.
   * En el caso de la division si ` y = 0`,NO se puede realizar la division, se muestra un mensaje y se hace `bandera = True` .
   * En el caso del logaritmo, si `x <= 0`, NO se puede calcular el logaritmo, se muestra un mensaje y se hace `bandera = True `.
5. se muestra el resultado en el caso en que `bandera = false`.

"Tomado de python con aplicaciones  a las matematicas, ingenieria y finanzas.
cervantes 0, baez d"
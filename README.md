# sesion7-tarea-grupo
Repositorio Sesión 7

Escribid un programa que permita jugar a una versión simplificada del Máster Mind. El objetivo del juego es adivinar una combinación secreta de cuatro dígitos distintos en sucesivos intentos y recibiendo la siguiente información del resultado de cada intento:

- número de dígitos acertados (dígitos de los que hemos acertado su valor y posición)
- número de dígitos casi (dígitos de los que hemos acertado su valor pero no su posición).

Cuando el jugador adivine la combinación secreta, el programa le informará del número de intentos que ha necesitado. También se puede finalizar porque el jugador abandona, aún así le debe informar de sus intentos.

Debes definir, al menos, las siguientes funciones:

- una función generar_combinacion_secreta() que devuelva una combinación secreta formada por cuatro dígitos diferentes obtenidos al azar,
- una función es_valida(combinacion) que devuelva true si la combinación pasada como parámetro es válida (la combinación la forman cuatro dígitos) y false en caso contrario,
- una función leer_combinacion() que pida por teclado una combinación hasta que sea válida y devuelva dicha combinación,
- una función calcular_acertados_casi (comb_secreta,  comb_jugada) que devuelva la cantidad de dígitos acertados y casi correspondientes a la jugada realizada cuando se compare con la combinación secreta.

Nota: entre paréntesis se indica los parámetros de entrada necesarios, si necesitas algún o algunos parámetros de salida deberás añadirlos.

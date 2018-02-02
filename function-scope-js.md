# Reconociendo Funciones 
 Leer el codigo javascript e identificar las funciones globales, locales, funciones de callback, expresions, statement, clousure, scope, contextos de ejecucion, que funciones forman parte de la pila de ejecucion (stack execution) y que funciones forman parte de la cola de eventos (event queue).

 ## Funciones Globales 

 * $(document).ready(function(){...}

 ## Funciones Locales 
 
 * function activeButton() 
 * function desactiveButton()
 * function longitud(input)
 * function soloNumeros(input)
 * function isValidCreditCard(numberCard)

 ## Funciones Callback 

 * $(document).ready(function(){...}
 * $inputCard.on('input', function(){...})
 * function isValidCreditCard... var creditCardNumber = soloNumeros(longitud(numberCard))

 ## Funcion Statement

 * function activeButton() 
 * function desactiveButton()
 * function longitud(input)
 * function soloNumeros(input)
 * function isValidCreditCard(numberCard)

 ## Clousure
 
 * $(document).ready(function(){...}
 * function isValidCreditCard(numberCard)

 ## Stack execution 

 * activeButton();
 * desactiveButton();

## Event Queue

*  $inputCard.on('input', function() {...})


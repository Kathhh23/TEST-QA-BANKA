ERROR 1: Al presionar boton "Ingresar numero aleatorio" no mostraba algun mensaje y no es funcional
SOLUCION: se debe a que addeventListener estaba escrito incorrecto en javascript las reglas son con camelcase addEventListener

ERROR 2: al ingresar los numeros no me coloca las pistas para poder adivinar el numero aleatorio
SOLUCION: mala estructura de los if y else

ERROR 3: const ATTEMPS = 5; declaracion de oportunidades en el juego
SOLUCION: const ATTEMPS = 10; 10 oportunidades correctas

ERROR 4: Numero aleatorio genera decimal y debe de ser entero
SOLUCION: Math.Floor(Math.random() * 100 ) + 1; floor

ERROR 5: const lowOrHi = document.querySelector('lowOrHi'); FALTABA PUNTO PARA LLAMAR A LA CLASE
SOLUCION : const lowOrHi = document.querySelector('.lowOrHi');

ERROR 6: no contaba con alerta si usuario ingresaba numero decimal
SOLUCION : Number.isInteger

ERROR 7: no contaba con alerta si usuario ingresaba numero mayor a 100 o menor a 1
SOLUCION : agregar condiciones para las alertas

ERROR 8: no contaba con alerta si usuario adivinaba numero correcto
SOLUCION : Number(userGuess)

El programa contaba convarios errores de logica y visuales y gramaticalmente.
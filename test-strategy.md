PLAN DE ATAQUE: 

Este plan de pruebas se ha desarrollado con el propósito de identificar y diagnosticar posibles defectos en el proyecto 
implementado en lenguajes de programación HTML y JavaScript. Su finalidad principal es evaluar y validar el funcionamiento 
del sistema con el objetivo de llevar a cabo una depuración efectiva de los errores detectados.

Errores corregidos:

1. En la declaración Math.random no se estaba multiplicando el rango de valores, sino el de intentos.  
La forma correcta es: 
let randomNumber = Math.floor(Math.random() * 100) + 1;
 
2. También se tenia un error en la generación de números, ya que no se estaba sumando el numero 1, al agregarlo se generan los números del 1 al 100.
randomNumber = Math.floor(Math.random() * 100) + 1;

3. En la selección de los elementos por clases se utiliza un punto antes de la clase, se cambió a esta forma:
const lowOrHi = document.querySelector('.lowOrHi');

4. La función addEventListener cuenta con mayúscula en la primera letra, se modifico a la forma correcta:
guessSubmit.addEventListener('click', checkGuess);
y 
resetButton.addEventListener('click', resetGame);

Estas correcciones técnicas han sido aplicadas con el propósito de garantizar el funcionamiento correcto del sistema y asegurar la efectividad de las pruebas. 
La revisión y validación de estas modificaciones son parte fundamental del proceso de aseguramiento de la calidad.

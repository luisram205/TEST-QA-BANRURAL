Linea 44:     let randomNumber = Math.random() * 10; se corrige let let randomNumber = (Math.floor() * 100) + 1;

Linea 46:  se verfica numero de intentos menor a lo solicitado const ATTEMPS = 5; y se corrige const ATTEMPS = 10;

Linea 49:  se detecta error en la funcion const lowOrHi = document.querySelector('lowOrHi'); y se corrige  const lowOrHi = document.querySelector('.lowOrHi');

Linea 58: no tiene un valor numerico let userGuess = guessField.value; se corrige let userGuess = number(guessField.value); 

Linea 65: alerta incorreta lastResult.textContent = '!!!Pérdistes!!!'; se corrige alerta lastResult.textContent = 'Felicitaciones! adivinaste el número!';

Linea 66:  alerta con color incorrecto lastResult.style.backgroundColor = 'black'; se corrige lastResult.style.backgroundColor = 'green';

Linea 70: alerta incorrecta lastResult.textContent = 'Felicitaciones! adivinaste el número!'; se corrige la alerta lastResult.textContent = '!!!Pérdistes!!!';

Linea 75:  alerta incorrecta lastResult.style.backgroundColor = 'green'; se correige lastResult.style.backgroundColor = 'black';

Linea 87: se detecta error en la funcion  se encuentra la funcion guessSubmit.addeventListener('click', checkGuess);
se corrige guessSubmit.addEventListener('click', checkGuess);

Linea 95:  se detecta funcion mal declarada resetButton.addeventListener('click', resetGame); y se corrige resetButton.addEventListener('click', resetGame);

Linea 114:  se dectar la funcion randomNumber = Math.floor(Math.random()) + 1; donde ya no tiene * 100 + 1 se correige de acuerdo a la correxion de la linea 44 

nota: se validad que no esta declara la funcion para realizar la evaluacion en la cual solo se permite ingresar numeros enteros la cual no lanza alertas

nota 2: se valida que los colores no fueron establecidos en hexadecimales

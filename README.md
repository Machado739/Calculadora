# Calculadora Machado Rodriguez Alexis

document.querySelector(".display");:
Esto selecciona el primer elemento HTML que tiene la clase CSS "display". En tu caso, parece que es el área de visualización de la calculadora. Al seleccionarlo de esta manera, puedes acceder y manipular ese elemento en tu código JavaScript.

const buttons = document.querySelectorAll("button");:
Esto selecciona todos los elementos HTML que son etiquetas <button> en tu documento HTML y los almacena en una NodeList (una colección de nodos). Esta línea de código te permite acceder a todos los botones de la calculadora y manipularlos.

buttonText = button.textContent;:
Esto asigna el contenido de texto del botón actual (representado por la variable button) a la variable buttonText. En otras palabras, obtiene el texto que se muestra en el botón y lo almacena en la variable buttonText.

buttons.forEach((button) => { ... }):
Esto utiliza el método forEach para iterar sobre todos los elementos en la NodeList llamada buttons. En este contexto, se está aplicando una función anónima (una función sin nombre) a cada botón en la NodeList. Dentro de esa función anónima, puedes realizar acciones en cada botón individualmente.

button.addEventListener("click", () => { }):
Esto agrega un "event listener" al botón actual (representado por la variable button). El event listener escucha el evento de clic en ese botón en particular. Cuando se hace clic en el botón, se ejecutará la función anónima proporcionada como segundo argumento. Esto te permite definir qué acciones deben realizarse cuando se hace clic en ese botón específico.

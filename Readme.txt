¿Qué hace `document.querySelector(".display");`?**
   `document.querySelector(".display");` es una expresión JavaScript que busca y selecciona el primer elemento en el documento HTML que tenga la clase CSS "display". Esto es útil cuando deseas manipular un elemento específico en la página web, como un elemento de pantalla.

¿Qué hace `const buttons = document.querySelectorAll("button");`?**
   `document.querySelectorAll("button");` selecciona todos los elementos `<button>` en el documento HTML y los almacena en la variable `buttons`. Esto crea una colección (nodelist) de todos los botones en la página que puedes utilizar para realizar operaciones en lotes.

 ¿Qué hace `buttonText = button.textContent;`?**
   `button.textContent` accede al contenido de texto dentro del elemento `button` y lo almacena en la variable `buttonText`. Esto te permite obtener el texto que se muestra en el botón y utilizarlo en tu código, como para mostrarlo en otro lugar de la página o realizar alguna operación basada en ese texto.

 ¿Qué hace y cómo funciona `buttons.forEach((button) => { ... })`?**
   `buttons.forEach((button) => { ... })` es un ejemplo de un bucle `forEach` que recorre cada elemento en la colección `buttons` (en este caso, todos los botones). Para cada botón, se ejecuta el código dentro del bloque de llaves `{ ... }`. Esto te permite realizar acciones específicas en cada botón de manera individual, como agregar eventos o modificar su contenido.

 ¿Qué hace y cómo funciona `button.addEventListener("click", () => { } )`?**
   `button.addEventListener("click", () => { } )` agrega un evento de escucha al elemento `button` que está destinado a responder cuando se hace clic en el botón. Cuando el botón se hace clic, se ejecutará el código dentro de la función anónima `() => { }`. Esto te permite definir acciones personalizadas que deben realizarse cuando un botón específico se hace clic, como cambiar el estado de la página o realizar una acción específica.
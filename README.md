# Prueba de Velocidad de Escritura

Este proyecto es una aplicación web simple para probar la velocidad de escritura de un usuario.  Se asemeja a juegos como MonkeyType, ofreciendo una interfaz limpia y funcional.

## Características:

*   **Interfaz de usuario:**  Diseño minimalista y moderno con un tema oscuro.
*   **Cronómetro:** Muestra el tiempo transcurrido durante la prueba.
*   **Resaltado de texto:** Resalta en verde las letras correctas y en rojo las incorrectas mientras el usuario escribe.
*   **Resultados:**  Al finalizar la prueba, muestra las palabras por minuto (WPM), el tiempo total y la cantidad de errores.
*   **Texto de prueba:** Incluye un texto de ejemplo para la prueba, pero se puede modificar fácilmente.

## Tecnologías utilizadas:

*   **HTML:** Para la estructura de la página web.
*   **CSS:** Para el diseño y estilo de la interfaz de usuario.
*   **JavaScript:** Para la lógica del juego, el cronómetro y el cálculo de los resultados.

## Instrucciones de uso:

1.  Clona el repositorio o descarga los archivos.
2.  Abre el archivo `index.html` en un navegador web.
3.  Comienza a escribir el texto que aparece en pantalla.
4.  Los resultados se mostrarán al finalizar la escritura del texto.


## Consideraciones adicionales:

*   El cálculo de palabras por minuto (WPM) se basa en una aproximación simple (número de caracteres / 5).
*   El código podría mejorarse añadiendo características adicionales, como la selección de diferentes textos de prueba, diferentes niveles de dificultad, y un sistema de guardado de puntuaciones.
*   La aplicación usa un temporizador simple basado en `setInterval`. Para una mayor precisión, se podría utilizar una librería de tiempo más robusta.


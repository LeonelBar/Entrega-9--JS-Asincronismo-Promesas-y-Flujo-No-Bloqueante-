# 🎮 Simulador de Super-Arcade — Pre-Entrega 9

Simulador interactivo de catálogo y compra de juegos de PlayStation 2 desarrollado con HTML5, CSS3 y JavaScript ES6+, incorporando asincronismo no bloqueante, promesas y manejo de errores.

## Novedades de la Pre-Entrega 9

- **Temporizador con `setTimeout()`**: muestra un aviso complementario unos segundos después de ingresar sin bloquear la interfaz.
- **Promesas y `async / await`**: simula la carga asíncrona del catálogo con `new Promise` y `setTimeout`, consumida mediante `await` con estados visuales en el DOM.
- **Manejo de errores con `try / catch / finally`**: protege la carga asíncrona y el envío del formulario, mostrando avisos claros ante fallos y cerrando el estado de forma consistente.

## Estructura del proyecto

- `index.html`: estructura en la raíz con `css/style.css` y `js/main.js` (`defer`) enlazados en el `<head>`.
- `css/style.css`: estilos dark mode, tarjetas en grilla y estados visuales.
- `js/main.js`: lógica de `Juego`, persistencia en `localStorage`, operaciones asíncronas y feedback 100% por el DOM (sin `alert`, `prompt` ni `console`).
- `img/`: portadas de los juegos e imagen por defecto.

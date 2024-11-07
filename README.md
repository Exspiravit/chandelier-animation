# Proyecto de Animación de Cuerdas

Este proyecto es una aplicación de animación interactiva que simula cuerdas utilizando HTML5 Canvas y JavaScript. Las cuerdas reaccionan a la posición del ratón, creando un efecto visual dinámico.

## Características

- Simulación de cuerdas con física básica.
- Interacción con el ratón para manipular las cuerdas.
- Renderizado en tiempo real utilizando `requestAnimationFrame`.

## Requisitos

- Un navegador web moderno que soporte HTML5 Canvas y JavaScript ES6.
- No se requieren dependencias externas.

## Instalación

1. **Clonar el repositorio:**

   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DEL_DIRECTORIO>
   ```

2. Abrir el archivo HTML: Abre el archivo index.html en tu navegador web preferido.

## Uso

1. Interacción:

- Mueve el ratón sobre el área del canvas para interactuar con las cuerdas.
- Las cuerdas reaccionarán a la posición del ratón, creando un efecto de atracción.

2. Personalización:

- Puedes ajustar los parámetros de las cuerdas, como el número de segmentos, el color, y la tensión, modificando el archivo script.js.

## Estructura del Código

- App: Clase principal que inicializa el canvas, maneja el redimensionamiento de la ventana y controla el ciclo de renderizado.
- Rope: Clase que representa una cuerda, compuesta por segmentos conectados por puntos.
- Dot: Clase que representa un punto en la cuerda, con propiedades físicas como fricción y gravedad.
- Stick: Clase que conecta dos puntos, manteniendo una longitud constante mediante la aplicación de tensión.
- Mouse: Clase que rastrea la posición del ratón y permite la interacción con las cuerdas.

## Detalles Técnicos

- Canvas: Se utiliza para dibujar las cuerdas y los puntos en la pantalla.
- Vector: Se asume que hay una clase Vector utilizada para manejar operaciones vectoriales como suma, resta y multiplicación.

## Créditos

Referencia: https://github.com/tharuncruz7/Chandelier-Animation

## Test

Puedes probarlo desde este enlace: https://chandelier-animation.netlify.app/

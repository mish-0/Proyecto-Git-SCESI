# Proyecto-Git-SCESI

## Proyecto: ¿Quién es ese Pokémon? — PokePibbles

Este es el repositorio oficial del proyecto desarrollado por el equipo PokePibbles para la Sociedad Científica de Estudiantes de Sistemas e Informática (SCESI). El objetivo es una aplicación web interactiva que utiliza lógica de filtrado para adivinar un Pokémon de la primera generación basado en las respuestas del usuario.

## Logros y Puntos Clave del Desarrollo

### Estructura de Navegación y Conectividad

**Separación de Estados:** Implementamos una arquitectura de dos páginas (index.html e index2.html) para separar el flujo de bienvenida de la lógica principal del juego.

**Conexión entre Páginas:** Se configuró la transición fluida mediante botones dinámicos y rutas relativas, permitiendo que el usuario inicie el juego sin recargas innecesarias del servidor.

## Interfaz Visual (UI) con Estilo "Comic-Pokémon"

**Diseño Moderno:** Utilizamos una paleta de colores basada en el rojo intenso (#b91c1c) y azul Pokémon (#3b4cca).

**Estética de Bordes:** Se aplicó un estilo de marco negro grueso (5px solid #000) en los contenedores e imágenes para emular la estética de los cómics y el arte de la franquicia.

**Responsive Design:** El diseño utiliza Flexbox para garantizar que los elementos se vean correctamente en diferentes tamaños de pantalla.

## Motor de Lógica y Base de Datos (Pokedex)

**Algoritmo de Filtrado:** Desarrollamos un motor en JavaScript que filtra un arreglo de objetos (Pokémon) en tiempo real basado en atributos como tipo, color y número de patas.

**Normalización de Datos:** Se estructuró la información de los Pokémon para permitir comparaciones lógicas precisas, reduciendo las opciones hasta dar con el resultado final.

## Pruebas de Rendimiento y Hardware

Para asegurar la fluidez del proyecto, se realizaron pruebas de ejecución y optimización en equipos de alto rendimiento:

**Hardware de Desarrollo:** Las pruebas técnicas y el debugging se realizaron principalmente en una laptop OMEN Transcend 14, asegurando tiempos de carga mínimos.

**Optimización en Java:** Como parte de la investigación previa del equipo, se analizaron algoritmos de eficiencia (como el cálculo de números de Dudeney) para entender el manejo de memoria en entornos de alto rendimiento.

## Tecnologías Utilizadas

**HTML5 / CSS3:** Para la estructura y el diseño visual personalizado.

**JavaScript (ES6+):** Para el motor de filtrado y la manipulación del DOM.

**Git / GitHub:** Para el control de versiones, manejo de ramas (develop, main, feat-\*) y colaboración grupal.

## Colaboradores

**Sebastian** (Lógica de filtrado, integración y pruebas de hardware).

**Matias** (Conectividad de páginas y estilos CSS).

**Leo:** Desarrollo de componentes y soporte en la lógica del motor de búsqueda.

**Mish:** Gestión del repositorio, revisión de código (Code Review) y supervisión de la rama develop.

# Smart-Travel

**Smart-Travel** es un juego interactivo que reta a los jugadores a resolver el **Problema del Agente Viajero (TSP)** mediante una interfaz gráfica. Los jugadores deben agregar ciudades a un mapa y luego tratar de encontrar la ruta más corta que las conecte todas.

## Objetivo del Juego

El objetivo principal es encontrar la ruta más corta posible que conecte todas las ciudades en el mapa, visitando cada una solo una vez y regresando al punto de origen.

- **Agregar Ciudades**: Los jugadores pueden hacer clic en el mapa para añadir ciudades.
- **Calcular Ruta**: Una vez que se han añadido ciudades, los jugadores pueden calcular la distancia total de la ruta que han creado.
- **Ruta Óptima**: El juego ofrece una ruta óptima calculada utilizando algoritmos de optimización, que el jugador puede comparar con su ruta.
- **Reiniciar**: Los jugadores pueden reiniciar el juego en cualquier momento para intentar nuevamente.

## Características Principales

- **Interfaz Gráfica Interactiva**: Los jugadores interactúan con el mapa agregando ciudades y trazando rutas.
- **Cálculo de Distancia en Tiempo Real**: El juego muestra la distancia de la ruta del jugador conforme se añaden más ciudades.
- **Algoritmo de Optimización**: Implementación de un algoritmo para encontrar la ruta óptima, como el algoritmo del vecino más cercano.
- **Aprendizaje Lúdico**: Combina teoría de grafos y optimización en una experiencia divertida y educativa.

## Cómo Jugar

1. **Iniciar Juego**: Al iniciar el juego, aparecerá un mapa en blanco.
2. **Agregar Ciudades**: Haz clic en el mapa para agregar una ciudad. Cada ciudad se conecta automáticamente con la anterior mediante una línea que representa la ruta.
3. **Calcular Distancia**: Haz clic en el botón "Calcular Distancia" para ver la distancia total de la ruta que has trazado.
4. **Ruta Óptima**: Compara tu ruta con la ruta óptima haciendo clic en el botón "Ruta Óptima".
5. **Reiniciar Juego**: Reinicia el juego en cualquier momento para comenzar de nuevo.

## Requisitos del Sistema

- **Android Studio** para el desarrollo de la aplicación Android.
- **Java** como lenguaje de programación principal.
- **Gradle** para la gestión de dependencias.

## Instalación

1. Clona este repositorio:
    ```bash
    git clone https://github.com/tuusuario/smart-travel.git
    ```

2. Abre el proyecto en **Android Studio**.

3. Compila y ejecuta el proyecto en un emulador o dispositivo Android.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el proyecto o agregar nuevas características, sigue los siguientes pasos:

1. Haz un fork de este repositorio.
2. Crea una nueva rama (`git checkout -b feature-nueva-funcionalidad`).
3. Haz tus cambios y haz commit (`git commit -m 'Añadir nueva funcionalidad'`).
4. Empuja los cambios a tu rama (`git push origin feature-nueva-funcionalidad`).
5. Crea un Pull Request.

## Licencia

Este proyecto se distribuye bajo la licencia MIT. Puedes ver más detalles en el archivo LICENSE.

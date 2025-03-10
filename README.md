# README - Página Web de Sorteo de Amigo Secreto

## Descripción
Esta página web permite a los usuarios organizar un sorteo de "Amigo Secreto". Los participantes pueden agregar sus nombres a una lista, y la aplicación seleccionará al azar un nombre de la lista como el "Amigo Secreto". La interfaz es sencilla y fácil de usar, con un diseño atractivo y responsive. Además, se ha implementado un botón para reiniciar el juego, lo que permite a los usuarios comenzar de nuevo sin necesidad de recargar la página.

---

## Funcionalidades
1. **Agregar nombres**: Los usuarios pueden ingresar nombres en un campo de texto y agregarlos a la lista de participantes.
2. **Validación de nombres**: 
   - No se permiten nombres vacíos.
   - No se permiten nombres duplicados.
3. **Mostrar lista de participantes**: Los nombres agregados se muestran en una lista en tiempo real.
4. **Sortear Amigo Secreto**: Al hacer clic en el botón "Sortear", se selecciona un nombre al azar de la lista y se muestra como el ganador.
5. **Reiniciar juego**: Un botón adicional permite reiniciar el juego, limpiando la lista de participantes y el resultado del sorteo.
6. **Diseño responsive**: La página está diseñada para adaptarse a diferentes tamaños de pantalla.

---

## Desarrollo del Proyecto

El desarrollo de este proyecto siguió los siguientes pasos:

1. **Descarga del proyecto y enlace con GitHub**: El proyecto se descargó inicialmente y se configuró para trabajar con control de versiones en GitHub.
2. **Trabajo en el código**: Se comenzó a trabajar en los archivos `index.html` y `app.js`, implementando la lógica básica del sorteo y la interfaz de usuario.
3. **Etapa Beta**: Una vez que la funcionalidad básica estuvo lista, se consideró que el código estaba en etapa Beta.
4. **Subida a GitHub**: Se subió la rama principal (`main`) a GitHub para mantener un respaldo del progreso.
5. **Rama secundaria**: Se creó una rama secundaria para trabajar en nuevas funcionalidades sin afectar la rama principal.
6. **Implementación del botón de reinicio**: Se agregó un botón para reiniciar el juego, aunque inicialmente no funcionaba correctamente debido a problemas con el tamaño del botón.
7. **Mejoras en el botón**: Se insertó un icono de "refresh" en el botón y se ajustaron los estilos en `style.css` para que los botones tuvieran un tamaño y alineación adecuados.
8. **Funcionamiento correcto**: Después de las correcciones, el código funcionó correctamente, incluyendo el botón de reinicio.
9. **Creación del README**: Se comenzó a trabajar en el archivo `README.md` para documentar el proyecto.
10. **Capturas de pantalla y video**: Se tomaron capturas de pantalla y se grabó un video para ilustrar el uso de la aplicación y agregarlos al `README`.
11. **README final**: Se completó la versión final del `README` con toda la información necesaria.

---

## Cómo funciona el código en `app.js`
El archivo `app.js` contiene la lógica principal de la aplicación. Aquí te explico cómo funciona:

1. **Array `amigos`**: Almacena los nombres de los participantes.
2. **Función `agregarAmigo`**:
   - Obtiene el valor del campo de texto.
   - Valida que el nombre no esté vacío ni duplicado.
   - Agrega el nombre al array `amigos` y actualiza la lista en la interfaz.
3. **Función `actualizarLista`**:
   - Limpia la lista actual y recorre el array `amigos` para mostrar los nombres en la interfaz.
4. **Función `sortearAmigo`**:
   - Selecciona un nombre al azar del array `amigos` utilizando `Math.random()`.
   - Muestra el nombre del ganador en la sección de resultados.
   - Habilita el botón "Juego nuevo" después de realizar el sorteo.
5. **Función `reiniciarJuegoAmigoSecreto`**:
   - Limpia el array `amigos`, la lista de participantes y el resultado del sorteo.
   - Deshabilita el botón "Juego nuevo" hasta que se realice un nuevo sorteo.
6. **Funciones adicionales**:
   - `limpiarCaja`: Limpia el campo de texto después de agregar un nombre.
   - `generarNumeroSecreto`, `condicionesIniciales`, y `reiniciarJuego`: Funciones relacionadas con un juego de número secreto (no utilizado en esta aplicación).

---

## Capturas de pantalla y videos
A continuación, se muestran imágenes y videos que ilustran cómo usar la aplicación:

### 1. Agregar nombres
![Captura de pantalla: Agregar nombres](ruta/a/captura1.png)  
*Descripción: Muestra el campo de texto y el botón "Añadir".*

### 2. Lista de participantes
![Captura de pantalla: Lista de nombres](ruta/a/captura2.png)  
*Descripción: Muestra la lista de nombres agregados.*

### 3. Realizar sorteo
![Captura de pantalla: Resultado del sorteo](ruta/a/captura3.png)  
*Descripción: Muestra el resultado del sorteo con el nombre del ganador.*

### 4. Reiniciar juego
![Captura de pantalla: Reiniciar juego](ruta/a/captura4.png)  
*Descripción: Muestra el botón de reinicio y la interfaz después de reiniciar el juego.*

### Video: Cómo agregar nombres y realizar el sorteo
## Video demostración

<div align="center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/fW5BpOruc9g?si=d4TwntJc2KFE6TDY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
[Ver video](ruta/a/video.mp4)  
*Descripción: Video que muestra el proceso completo de agregar nombres, realizar el sorteo y reiniciar el juego.*

---

## Instrucciones de uso
1. Abre la página web en tu navegador.
2. Ingresa el nombre de un participante en el campo de texto y haz clic en "Añadir".
3. Repite el paso anterior para agregar más nombres.
4. Una vez que todos los nombres estén en la lista, haz clic en "Sortear" para seleccionar al azar un Amigo Secreto.
5. El resultado se mostrará en la sección inferior.
6. Si deseas reiniciar el juego, haz clic en el botón "Juego nuevo".

---

## Tecnologías utilizadas
- **HTML**: Estructura de la página.
- **CSS**: Estilos y diseño responsive.
- **JavaScript**: Lógica de la aplicación.

---

## Contribuciones
Si deseas contribuir a este proyecto, ¡eres bienvenido! Puedes hacerlo mediante:
- Reportar errores o sugerir mejoras.
- Realizar pull requests con nuevas funcionalidades o correcciones.

---

## Licencia
Este proyecto está bajo la licencia [MIT](LICENSE).

---

¡Gracias por usar nuestra aplicación de Sorteo de Amigo Secreto! Esperamos que sea útil y divertida para ti y tus amigos.
# Games Opinion GO

Games Opinion GO es una aplicación web que permite a los usuarios explorar y calificar sus juegos favoritos. Los usuarios pueden ver una lista de juegos, dar sus opiniones y dar "Me gusta" a sus juegos preferidos. La aplicación también incluye una página de administración donde los usuarios pueden gestionar sus cuentas y comprar "Coins" dentro de los juegos que les gustan.

## Configuración del Proyecto

Para ejecutar el proyecto Games Opinion GO, sigue estos pasos:

1. Clona el repositorio en tu máquina local.

2. Instala las dependencias necesarias con el siguiente comando:

   ```bash
   npm install
   ```

3. Ejecuta la aplicación con el siguiente comando:

   ```bash
   npm run serve
   ```

4. Abre tu navegador web y navega a `http://localhost:8080/` para acceder a la aplicación.

## Estructura del Proyecto

El proyecto está estructurado de la siguiente manera:

- Directorio `src`: Contiene todo el código fuente de la aplicación.

  - Directorio `assets`: Contiene imágenes y otros activos estáticos utilizados en la aplicación.

  - Directorio `components`: Contiene componentes de Vue.js utilizados en diferentes vistas de la aplicación.

  - Directorio `views`: Contiene vistas de Vue.js para diferentes páginas de la aplicación.

  - `App.vue`: Componente principal que sirve como punto de entrada para la aplicación.

  - `main.js`: Archivo JavaScript principal que inicializa la aplicación Vue.js.

## Vistas

1. **HomeView** (`HomeView.vue`):
   - Muestra una lista de juegos con sus respectivos detalles, como nombre, calificación, fecha de lanzamiento y última actualización.
   - Permite a los usuarios dar su opinión sobre un juego y darle "Me gusta".
   - Incluye navegación a las vistas "Opinión" y "Administración".

2. **OpinionView** (`OpinionView.vue`):
   - Permite a los usuarios dar su opinión sobre un juego que han seleccionado desde HomeView.
   - Muestra la última opinión dada por el usuario y una lista de todas las opiniones para ese juego.
   - Proporciona opciones para editar o eliminar la última opinión.

3. **AdministrationView** (`AdministrationView.vue`):
   - Muestra la información de la cuenta del usuario, incluido el nombre y apellido.
   - Permite a los usuarios ingresar su nombre y apellido para la gestión de la cuenta.
   - Proporciona un botón para navegar a la vista "Coins".

4. **ResumeView** (`ResumeView.vue`):
   - Muestra un resumen de la cuenta del usuario y del último juego que le gustó.
   - Ofrece una opción para agregar "Coins" para el último juego que le gustó.

5. **NotFoundView** (`NotFoundView.vue`):
   - Muestra una página de error cuando no se encuentra la página solicitada (Error 404).

## Estilos

La aplicación utiliza CSS para los estilos. Incluye estilos para diferentes componentes y vistas para crear una interfaz de usuario estéticamente atractiva.

## Integración de API

La aplicación obtiene datos de juegos utilizando la API de RAWG (https://rawg.io/apidocs) para mostrar una lista de juegos. También permite a los usuarios dar opiniones sobre juegos y darles "Me gusta".

## Almacenamiento Local

La aplicación utiliza el almacenamiento local del navegador para guardar datos del usuario y realizar un seguimiento del último juego que le gustó. También utiliza el almacenamiento local para gestionar la información de la cuenta del usuario.


## Ejecutar la Aplicación

Para ejecutar la aplicación Games Opinion GO, sigue las instrucciones de configuración del proyecto y accede a ella a través de tu navegador web. Podrás explorar juegos, dar opiniones, dar "Me gusta" a juegos y gestionar tu cuenta de manera eficiente.

¡Disfruta usando Games Opinion GO!

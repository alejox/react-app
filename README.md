# Aplicación de Academia de Música con Rutas Protegidas ![Alt text](image-1.png)

Esta aplicación fue desarrollada en React y presenta funcionalidades de rutas protegidas para ofrecer contenido exclusivo a los usuarios registrados.

## Inicio del Proyecto

Para ejecutar el proyecto, utiliza el siguiente comando:

```sh
npm run dev
```

## Tecnologías Utilizadas 🛠️

Se utilizaron las siguientes tecnologías y bibliotecas:

* Bootstrap
* Axios
* Sass

## Descripción 📚

La aplicación simula una academia de música y presenta las siguientes características:

Página de inicio con contenido visible para todos los usuarios, que muestra información sobre los profesores disponibles generados de manera aleatoria.

Registro de usuarios para acceder a contenido exclusivo.

Rutas protegidas para el contenido exclusivo de los usuarios registrados.

### Secciones con contenido exclusivo

* Actividades (Activities)
* Lección del Día (Day Lesson)

Autenticación
Para acceder al contenido exclusivo, los usuarios deben iniciar sesión utilizando las siguientes credenciales:

* Nombre de usuario: JohnDoe
* Contraseña: 1234
* Si un usuario no registrado intenta acceder al contenido protegido, será redirigido a la ruta raíz ("/").

### Consumo de API 🤖

La aplicación consume dos API's para obtener información adicional:

* API de Profesores Aleatorios: Genera profesores aleatorios y los muestra en la página de inicio.

* API de Tareas en Actividades: Genera tareas para la sección de "Actividades" (Activities).

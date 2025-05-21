-HeroesApp
-
- Es una apliacion desarrollada con Angular para gestionar una catalogo de heroes. Implementa la Arquitectura Modular, ademas de trabajar con rutas hijas y carga perezosa (lazy load). 
- Permite realizar operacion CRUD (Create, Read, Update, Delete), ademas de contar con un diseño responsivo

-Objetivo del Proyecto
-
Construir una SPA (Single Page Application) que sea eficiente, ligera y escalable aplicando las siguientes técnicas:
- Rutas hijas con carga perezosa
- CRUD (Crear, Leer, Actualizar, Eliminar)
- Comunicación entre componentes
- Modularización del código

-Tecnologias Utilizadas para su Desarrollo
-
- Angular **v16.2.0**
- Angular Material **v16.2.14**
- Angular Flex Layout **v15.0.0-beta.42**
- RxJS **v7.8.0**
- JSON Server (para simular una API REST)
- Quicktype (generación de interfaces TypeScript)
- Postman (para pruebas de endpoints)

-Instrucciones
-
- Descargar el Repositorio

*git clone https://github.com/AngelJAQ/ProyectoApp.git
cd ProyectoApp/heroesApp*

- Instala las dependencias del proyeto

En una terminal (puede ser la que incluye VS Code o el propio CMD) tendras que navegar hasta la carpeta del proyecto: heroesApp y ejecutar el siguiente comando:

*npm install*

en esta parte tendras que esperar a que se instalen las dependencias necesarias para ejecutar el proyecto

- Instala JSON-SERVER de Manera Global

Ahora, para instalar JSON-Server de Manera Global, bastara con ejecutar el siguiente comando, pero debera ser en el CMD Modo Administrador:

*npm install -g json-server*

- Levanta el Servidor

Aca desde una terminal, tendras que navegar hasta la carpeta heroes-server y ejecutar el siguiente comando:

*json-server --watch db.json*

- Corre la Aplicacion

En una terminal, navegaremos hasta la carpeta heroesApp donde ejecutaremos la apliacion con el comando:

#ng serve -o -

este comando nos abrira de manera automatica una pestaña en el navegador Chrome, en caso de ya tener la pagina solo bastara con ejecutar:

#ng serve

con este, solo sera necesario recargar la pagina.

nota: el "-o" hace que la ventana de Chrome se abra

-Estructura del Proyecto
-
ProyectoApp/
- heroesApp/         # Aplicación Angular
- heroes-server/     # Backend simulado con JSON Server

-Desarrollado por:
-
Alumnos de la Benemerita Universidad Autonoma de Puebla 
Facultad de Ciencias de la Computación

- Ronaldo Galicia Vázquez – 202126612
- Eduardo Portillo Fuentes – 202141836
- Angel Jesús Atenco Quiroz – 202117221

# TrelloJS

Práctica 7 de la semana 4 de LaunchX Backend NodeJS que consiste en un proyecto que conecte con la API de Trello JS.

### ¿Qué es trello?

[Trello](https://trello.com/) es una herramienta flexible para la gestión del trabajo, con la que los equipos pueden diseñar planes, colaborar en proyectos, organizar flujos de trabajo y hacer un seguimiento del progreso de una manera visual, productiva y gratificante.

Crear una cuenta en la plataforma es bastante sencillo, solo da clic [aquí](https://trello.com/es/signup) para redirigirte al formulario de registro.

### ¿Qué es una API REST?

Una API de REST, o API de RESTful, es una interfaz de programación de aplicaciones (API o API web) que se ajusta a los límites de la arquitectura REST y permite la interacción con los servicios web de RESTful.

En otras palabras, las API le permiten interactuar con una computadora o un sistema para obtener datos o ejecutar una función, de manera que el sistema comprenda la solicitud y la cumpla. (Red Hat, 2020).

### Documentación de su API.

En el presente [enlace](https://developer.atlassian.com/cloud/trello/rest/api-group-actions/) obtenemos la documentación de la API Rest de la plataforma Trello, la cual con a partir de unas credenciales (key, y token de tu cuenta registrada) tienes la oportunidad de interactuar con tus espacios de trabajo y tableros para crear cards (tarjetas, tareas), editar información, consultarla y mucho, mucho más.

### Dependencias.

Las dependencias instaladas en el proyecto se enlistan a continuación:

* ***express**:* es un framework escrito en JavaScript y alojado dentro del entorno de ejecución NodeJS que permite crear aplicaciones web.
* ***trello***: contenedor para algunas de las llamadas de la API Restful de Trello.

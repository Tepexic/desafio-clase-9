# Desafío clase 9

Utilizando la misma API de productos del proyecto entregable de la clase anterior, construir un web server (no REST) que incorpore:

- Un formulario de carga de productos en la ruta raíz (configurar la ruta '/productos' para recibir el POST, y redirigir al mismo formulario).
- Una vista de los productos cargados (utilizando plantillas de handlebars) en la ruta GET '/productos'.

Ambas páginas contarán con un botón que redirija a la otra.

## Instalación

`npm install`

## Ejecución

Con nodemon:

`nodemon server.js`

O bien:

`npm run serve`

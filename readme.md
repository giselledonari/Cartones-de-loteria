# Generador de Cartones de Lotería

Este proyecto es un generador de cartones de lotería que permite crear y almacenar cartones con 15 números al azar del 1 al 30. El objetivo de este proyecto es ofrecer una herramienta sencilla para generar cartones de lotería y almacenarlos para su posterior uso en sorteos o juegos de lotería.

## Funcionalidades

El proyecto cuenta con las siguientes funcionalidades:

- Generación de 5 cartones iniciales: Al cargar la página principal del proyecto se muestran 5 cartones iniciales generados aleatoriamente.
- Creación de nuevos cartones: En la página "Nuevo" se puede crear un nuevo cartón de lotería con 15 números al azar del 1 al 30. Los nuevos cartones se almacenan en un archivo JSON utilizando la librería fs para su posterior uso.
- Visualización de todos los cartones generados: En la página "Lista" se muestra una lista con todos los cartones generados hasta el momento, incluyendo los 5 cartones iniciales y los cartones generados mediante la funcionalidad de creación de nuevos cartones.
- Reinicio de los cartones: En la página "Lista" se incluye un botón para reiniciar los cartones y volver a los 5 iniciales generados aleatoriamente.

## Tecnologías utilizadas

El proyecto está desarrollado utilizando las siguientes tecnologías:

- HTML
- CSS
- JavaScript
- Node.js
- Express
- JSON
- fs

## Instalación y uso

Para utilizar el proyecto en tu ordenador, sigue los siguientes pasos:

1. Clona el repositorio en tu ordenador.
2. Instala las dependencias del proyecto mediante el siguiente comando en tu terminal: npm install
3. Inicia el servidor del proyecto mediante el siguiente comando: node server.js


4. Abre el navegador y accede a la dirección http://localhost:3000 para utilizar el proyecto.

## Capturas de pantalla

Página principal del proyecto:

![Pagina deinicio](https://github.com/giselledonari/Cartones-de-loteria/blob/main/git/scr1.PNG)

Página de creación de nuevos cartones:

![Nuevos Cartones](https://github.com/giselledonari/Cartones-de-loteria/blob/main/git/scr2.PNG)

Página de visualización de todos los cartones:

![Todos los cartones](https://github.com/giselledonari/Cartones-de-loteria/blob/main/git/scr3.PNG)



---
layout: post
title: "Instalar Node.js y npm"
description: Como instalar node.js y el gestor de paquetes npm.
image: 'http://res.cloudinary.com/ernestoaguaysol/image/upload/c_fill,h_399,w_760/v1508424077/nodeNPM_er5vhd.jpg'
category: 'instalar'
tags:
- node
- npm
twitter_text: Como instalar node.js y el gestor de paquetes npm.
introduction: Veremos que el node.js y el gestor de paquetes npm para desarrollar aplicaciones del lado del servidor.
---

<a href="https://nodejs.org/es/">Node.js</a>

Node es un intérprete *Javascript* del lado del servidor que cambia la noción de cómo debería trabajar un servidor. Su meta es permitir a un programador construir aplicaciones altamente escalables y escribir código que maneje decenas de miles de conexiones simultáneas en una sólo una máquina física.


<a href="https://www.npmjs.com/">Npm</a>

npm *(node package manager)* es un gestor de paquetes de **node.js**, que nos permite descargar librerías y enlazarlas o descargar programas de js

> El ecosistema de paquetes de **Node.js**, **npm**, es el ecosistema mas grande de librerías de código abierto en el mundo..

## Instalar Node.js y npm

Descargar el instalador de [node.js](https://nodejs.org/es/). Recomendable que sea de soporte extendido LTS.

- Ejecutamos el instalador.
- Aceptamos los términos y condiciones.
- Y luego continuamos con el famoso siguiente siguiente las instalaciones de windows.
- El paquete **npm** viene incluido dentro del instalador de **node.js**.
- Luego se instalará node.js junto con npm.

Y eso es todo...

## Verificar las versiones instaladas de Node.js y Npm 

Para saber que realmente instalamos todo correctamente abrimos la consola cdm y ejecutamos los comandos `node -v` y `npm -v`, nos quedaría algo como esto:

```
C:\> node -v
v6.11.3
C:\> npm -v
3.10.10
```

Y así concluimos con la instalación y verificación de las versiones instaladas.


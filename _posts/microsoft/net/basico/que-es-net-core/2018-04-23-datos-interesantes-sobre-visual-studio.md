---
layout: post
title:  "Datos interesantes sobre Visual Studio"
date:   2018-04-23 00:00:00 -03 
category: net-basico
tags: ["¿Qué es .NET Core?"]
---

<img src="/asset/img/que-es-net-core.png" class="img-responsive" alt="¿Qué es .NET Core?">

[< Volver a la serie](/que-es-net-core/)

Visual Studio posee muchas características que facilitan la creación de aplicaciones, por lo que vamos a hacer un repaso de las que tenés que conocer al comenzar en .NET.  

## IntelliSense

IntelliSense es una tecnología que facilita la escritura de código dándonos pistas de qué es lo que existe y qué podemos utilizar.  
A medida que vamos escribiendo, nos aparece una ventanita con opciones que podemos elegir, lo cual evita que nos equivoquemos al escribir y mejoremos la velocidad al tener que teclear menos caracteres.  

<img src="/asset/img/que-es-net-core/09.png" class="img-responsive" alt="¿Qué es .NET Core?">

Para seleccionar una opción de la lista podemos apretar `Tab` o `Enter`.

Si algo que queremos escribir no aparece en el IntelliSense es que no está disponible en ese contexto.

## Lista de errores

Si cometemos un error que Visual Studio pueda detectar antes de ejecutar el programa, al querer ejecutarlo nos aparecerá un mensaje como el siguiente:

<img src="/asset/img/que-es-net-core/10.png" class="img-responsive" alt="¿Qué es .NET Core?">

Al apretar `No`, se nos mostrará una ventana llamada Lista de errores

<img src="/asset/img/que-es-net-core/11.png" class="img-responsive" alt="¿Qué es .NET Core?">

Esta ventana nos indica en qué archivo se encontró el error, en qué línea, la descripción y un enlace para buscar más ayuda.  
Haciendo doble click sobre la descripción nos llevará directamente a la línea del error, con lo que nos ahorraremos mucho tiempo.  

## Explorador de soluciones

Esta ventana que en general se encuentra a la derecha de la pantalla (en caso que no la veas podés abrirla con `Ctrl+Alt+L`) te muestra todos los archivos que componen la solución. Es la forma más simple de ordenar, agregar y eliminar archivos.

<img src="/asset/img/que-es-net-core/12.png" class="img-responsive" alt="¿Qué es .NET Core?">

[< Volver a la serie](/que-es-net-core/)
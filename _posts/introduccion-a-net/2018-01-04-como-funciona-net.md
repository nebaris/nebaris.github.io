---
layout: post
title:  "¿Cómo funciona .NET?"
date:   2018-01-04 00:00:00 +03
category: net
tags: [Introduccion a .NET]
---
.NET Framework consta de dos componentes principales: 

1. Common Language Runtime (CLR) 
2. y la biblioteca de clases de .NET Framework. 

Common Language Runtime es el fundamento de .NET Framework.  
El runtime se puede considerar como un agente que administra el código en tiempo de ejecución y proporciona servicios centrales, como:  

- la administración de memoria
- la administración de subprocesos 
- y la comunicación remota

A su vez, aplica una seguridad de tipos estricta y otras formas de especificación del código que promueven su seguridad y solidez.  
El concepto de administración de código es un principio básico del motor en tiempo de ejecución. El código destinado al runtime se denomina código administrado, a diferencia del resto de código, que se conoce como código no administrado.  

La biblioteca de clases es una colección completa orientada a objetos de tipos reutilizables, que se pueden emplear para desarrollar aplicaciones que abarcan desde: las tradicionales herramientas de interfaz gráfica de usuario (GUI) o de línea de comandos, hasta las aplicaciones basadas en ASP.NET.  

.NET Framework puede hospedarse en componentes no administrados que cargan el Common Language Runtime en sus procesos e inician la ejecución de código administrado, con lo que se crea un entorno de software que usa características administradas y no administradas.  

En .NET Framework no solo se ofrecen varios hosts de tiempo de ejecución, sino que también se admite el desarrollo de estos hosts por parte de terceros. Por ejemplo, ASP.NET hospeda el motor en tiempo de ejecución para proporcionar un entorno de servidor escalable para el código administrado. ASP.NET trabaja directamente con el tiempo de ejecución para habilitar aplicaciones de ASP.NET y Servicios web XML.  

En la ilustración siguiente se muestra la relación de Common Language Runtime y la biblioteca de clases con las aplicaciones y el sistema en su conjunto. En la ilustración se representa igualmente cómo funciona el código administrado dentro de una arquitectura mayor.

<img src="{{ "/asset/img/introduccion-a-net/01.gif" | prepend: site.baseurl }}" class="img-thumbnail img-responsive center-block" />
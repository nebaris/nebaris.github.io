---
layout: post
title:  "Entendiendo .NET"
date:   2018-04-20 00:00:00 +03
category: net-basico
tags: ["¿Qué es .NET Core?"]
---

![¿Qué es .NET Core?](/asset/img/que-es-net-core.png "¿Qué es .NET Core?")

[< Volver a la serie](/que-es-net-core/)

Al entrar en el mundo de desarrollo de Microsoft podemos enterarnos que existen varios frameworks:

- .NET Framework
- Mono
- .NET Core
- .NET Standard

Todos estos frameworks están relacionados y permiten construir aplicaciones y servicios a los desarrolladores.

## .NET Framework

La plataforma de Microsoft .NET Framework incluye al CLR (Common Language Runtime) que la administra de la ejecución del código y provee una extensa biblioteca de clases.  
Fue creada en el 2002 para actualizar su suite de desarrollo y mejorar la forma de programar que venía de los 90. Una de las novedades más interesantes era la de poder desarrollar aplicaciones en el framework con diferentes lenguajes. Los dos principales fueron Visual Basic.NET y C#.  
Este framework fue creado con la posibilidad de ser multiplataforma, pero en ese entonces Microsoft puso todo su esfuerzo sobre el sistema operativo Windows. Es por esto que casi no se utilizaba este framework fuera de Windows.

## Mono y Xamarin

Mono es una implementación de .NET desarrollada por terceros. Es multiplataforma y la base de la plataforma móvil Xamarin.  
Microsoft compró a Xamarin en el 2016, la cual era una extensión para desarrollo bastante cara. Actualmente se distribuye de forma gratuita con Visual Studio 2017.  
La herramienta Xamarin Studio fue renombrada como Visual Studio para Mac y se le incluyó la capacidad de crear servicios ASP.NET Core Web Api.  
Xamarin se utiliza para desarrollos móviles y construir servicios en la nube para apps.  
Para leer más sobre el proyecto Mono podés entrar a la web oficial: [www.mono-project.com](http://www.mono-project.com/)

## .NET Core

Las aplicaciones móviles y el desarrollo en la nube hicieron a Windows un sistema operativo mucho menos importante a la hora del desarrollo. Es por esto que Microsoft comenzó a trabajar en un desacople del framework .NET del sistema operativo Windows.  
Al rescribir el framework para hacerlo realmente multiplataforma, Microsoft aprovechó para refactorizar y quitar todas las partes que ya no son consideradas centrales.  
Este nuevo producto se denominó .NET Core. Contiene una versión multiplataforma del CLR ahora denominada CoreCLR y una biblioteca de clases conocida como CoreFX.  
.NET Core es mucho más liviano que su sucesor ya que muchas características fueron quitadas, por ejemplo:

- Windows Forms y Windows Presentation Foundation (WPF), que se utilizaban para crear aplicaciones para Windows con interfaz de usuario.  
- ASP.NET Web Forms y Windows Communication Foundation (WCF), que se utilizaban para crear páginas y servicios web.
- ASP.NET MVC y ASP.NET Web API se refactorizaron y combinaron en un nuevo producto llamado ASP.NET Core.
- Entity Framework también fue puesto a dieta y renombrado como Entity Framework Core.

Para mejorar el rendimiento, Microsoft no sólo achicó el framework, sino que también lo modularizó en paquetes de NuGet (el administrador de paquetes de .NET), para poder utilizar pequeños bloques de funcionalidad de manera independiente.

## .NET Standard

Actualmente existen 3 plataformas .NET todas ellas controladas por Microsoft:

- .NET Framework
- .NET Core
- Xamarin

Cada una con diferentes fortalezas y debilidades ya que fueron creadas para diferentes escenarios. Esto conlleva a que un desarrollador tenga que aprender 3 plataformas distintas.  
Para paliar la situación, Microsoft definió el .NET Standard 2.0; que es una especificación que las plataformas .NET deben implementar.  
Para utilizar el .NET Standard hay que instalar una plataforma que implemente dicha especificación.  
El siguiente diagrama indica cómo funcionan las diferentes versiones.  

![¿Qué es .NET Core?](/asset/img/que-es-net-core/01.png "¿Qué es .NET Core?")

[< Volver a la serie](/que-es-net-core/)
---
layout: post
title:  "Primer programa en .NET Core"
date:   2018-04-22 00:00:00 -03
category: [net-basico, csharp-basico]
tags: ["¿Qué es .NET Core?"]
---

<img src="/asset/img/que-es-net-core.png" class="img-responsive" alt="¿Qué es .NET Core?">

[< Volver a la serie](/que-es-net-core/)

Para crear un programaba básico, el famoso "Hola mundo", voy a estar utilizando Visual Studio 2017.  
Para empezar vamos a crear un nuevo proyecto; para eso vamos a `Archivo > Nuevo > Proyecto`

<img src="/asset/img/que-es-net-core/06.png" class="img-responsive" alt="¿Qué es .NET Core?">

De todas las opciones que aparecen, buscamos en la barra de la izquierda el lenguaje `Visual C#`, del menú elegimos `.NET Core` y en la lista del centro elegimos `Aplicación de consola`.  
Ponemos `HolaMundo` como nombre y aceptamos.  

<img src="/asset/img/que-es-net-core/07.png" class="img-responsive" alt="¿Qué es .NET Core?">

Al terminar de cargar la plantilla del nuevo proyecto, nos aparecerá el siguiente código

{% highlight csharp %}

namespace HolaMundo
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
        }
    }
}

{% endhighlight %}

Este es el mínimo código necesario para escribir un programa en .NET Core con el lenguaje C#.  
Para ver nuestro programa basta con ir a `Depurar > Iniciar sin depurar` o apretar las teclas `Ctrl+F5`.
Visual Studio compilará la aplicación y la podremos ver una ventana de comandos.  

<img src="/asset/img/que-es-net-core/08.png" class="img-responsive" alt="¿Qué es .NET Core?">

[< Volver a la serie](/que-es-net-core/)
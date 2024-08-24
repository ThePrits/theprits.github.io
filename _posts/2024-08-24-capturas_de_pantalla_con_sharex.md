---
title: Capturas de Pantalla con ShareX
description: >-
  La mejor herramienta para sacar capturas de pantalla en Windows y MacOS.
author: pritam
date: 2024-08-24 00:00:00 +0800
categories: [Herramientas, Consejos]
tags: [aplicaciones, opensource]
image:
  path: /assets/img/post_20240823/cover.jpg

---

ShareX es una aplicación gratuita y de código abierto diseñada principalmente para hacer capturas de pantalla. Además de esta funcionalidad, también podrás grabar GIFs, vídeos, utilizar tecnología OCR en las capturas de texto, entre otras.

En este post enseñaré mi configuración de ShareX y cómo llegar a ella; ya que al principio la configuración de la aplicación puede ser algo confusa.

# ¿Cómo conseguir ShareX?

Actualmente ShareX está disponible para Windows y Mac, y puede ser descargado desde su [sitio web oficial](https://getsharex.com/) o el repositorio de winget:

```shell
winget ShareX.ShareX
```

Una vez instalado, la aplicación se ejecutará por defecto cada vez que se inicie el equipo. En este momento, ShareX estará configurado con sus parámetros predeterminados.

Lo primero que hay que hacer es abrir las "opciones de la aplicación" (no confundir con "opciones de tarea").

![Opciones](/assets/img/post_20240823/Q2CTX6g08R.png)

Aquí podremos configurar el comportamiento del programa.

## Integración

Aquí tenemos opciones importantes sobre el comportamiento del programa y su integración con el menú contextual (menú del clic derecho).

![Integración](/assets/img/post_20240823/ShareX_XOgxfaIv9u.png)

Lo más relevante aquí:

1. ACTIVADO: Iniciar ShareX cada vez que se inicie el sistema.
2. DESACTIVADO: Desactiva la funcionalidad para compartir en la web tus capturas con Imgur.
3. ACTIVADO: Permite abrir el editor de imágenes de ShareX al hacer clic derecho en una imagen (no necesariamente tomada con ShareX).

# Opciones de Tarea

Este menú nos permite configurar y decidir lo que el programa hará al momento de hacer las capturas de pantalla.

![Opciones de Tarea](/assets/img/post_20240823/tdAv0ZrH34.jpg)

## Carpeta para las Capturas de Pantalla

Las capturas de pantalla se guardarán de manera predeterminada en la carpeta de ShareX. Para mayor facilidad, es mejor mover la ruta de almacenamiento a la carpeta de Imágenes de Windows, o la carpeta de Capturas de Pantalla predeterminada de Windows.

![Carpeta Predeterminada](/assets/img/post_20240823/ShareX_eqxU0PmOUQ.png)

Simplemente tenemos que usar el buscador de la aplicación para elegir la carpeta de destino. En mi caso, es la carpeta de Capturas de Pantalla predeterminada de Windows (dentro de la carpeta Imágenes).

Asimismo, podemos elegir el formato predeterminado en el que se guardarán las capturas. En mi caso es .png.

![Formato de Imagen](/assets/img/post_20240823/ShareX_UIn8LsY2FP.png)

## Configuración de Teclas

Por defecto, una vez instalado e iniciado ShareX, se activará al accionar la tecla PrintScreen. Mi configuración es la siguiente:

![Hotkeys](/assets/img/post_20240823/ShareX_V8Y6DCbVx5.png)

* PrintScreen: Capturar una región de la pantalla.
* CTRL + PrintScreen: Capturar la pantalla entera.
* ALT + PrintScreen: Capturar la ventana seleccionada.
* SHIFT + PrintScreen: Inciar o parar la grabación de la pantalla.
* CTRL + SHIFT + PrintScreen: Iniciar o parar la grabación de un GIF.

## Vista Previa

Un paso muy importante es configurar qué queremos hacer después de hacer la captura de pantalla. En este menú lo más importante es:

![Acciones](/assets/img/post_20240823/ShareX_uXUDVZ2sTM.png)

* Placement: Elegir en qué lugar de la pantalla aparecerá la vista previa de nuestra captura.
* Left Click Action: Qué ocurrirá si hacemos clic derecho en la imagen.

En mi caso, me gusta que la acción con el botón derecho me abra el editor de imágenes de ShareX.

# Editor de Imágenes

Cada vez que se tome una captura de pantalla, aparecerá brevemente una miniatura en la parte inferior derecha de la pantalla. Si hacemos clic en ella, se abrirá el editor de imágenes (si es que hemos configurado esta opción en pasos anteriores).

![Editor](/assets/img/post_20240823/YuiN8Hc9Bo.png)

Aquí disponemos de varias herramientas para editar nuestra captura:

1. Guardar y Guardar como...
2. Copiar la imagen actual al portapapeles.
3. Rectángulo y Círculo.
4. Flecha.
5. Herramienta de Texto.
6. Lupa (amplía la selección).
7. Desenfocar o Pixelear.
8. Destacador.
9. Cambiar el color del objeto (flecha, círculo, rectángulo, ...)

# Captura de Vídeo y GIF

Además de hacer capturas de pantalla, ShareX permite hacer grabaciones de vídeo en formato .mp4.

Se puede abrir la capturadora con el atajo de teclado o seleccionandola en el menú desplegable de la aplicación.

![Vídeo](/assets/img/post_20240823/IE5wF7naPb.png)

La funcionalidad para grabar GIFs está en el mismo menú.

![GIF](/assets/img/post_20240823/EnMP5SVxJr.png)

Los vídeos y los GIFs se guardarán en la misma carpeta en la que se guardan las capturas.

# Otras funcionalidades y más información...

Si quieres conocer más sobre la funcionalidades de ShareX, puedes consultar su [documentación]().

Asimismo, recomiendo echar un vistazo al curso creado por Camilo Cruz en su [canal de YouTube](https://www.youtube.com/@reperio624/videos):

{% include embed/youtube.html id='NCFPNWpTXc0' %}

<br>

<p style="font-size: smaller;">📸 Créditos de las fotos de <em>preview</em> y <em>cover</em>: Joshua Willson y ShareX.</p>
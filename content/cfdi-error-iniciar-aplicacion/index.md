---
title: No se puede iniciar la aplicación
date: 2018-12-05
author: iscasur
modifiedDate: null
description: "Solución al error 'No se puede iniciar aplicación'"
---
### Problema
Al iniciar el programa de timbrado nos aparece el siguiente mensaje: "No se puede iniciar la aplicación".

![No se puede iniciar la aplicación](https://todoconta.s3-us-west-1.amazonaws.com/soporte/no-se-puede-iniciar-la-aplicacion.png)

No se puede iniciar la aplicación. Póngase en contacto con el proveedor de la aplicación.

### Solución

Este mensaje error sucede ya que los archivos de actualización de la aplicación se bajaron incompletos (por interrupciones en el Internet) de ahí que se descargan de manera corrupta por lo que tenemos que eliminarlos.

Ingresamos al Explorador de archivos de Windows y nos dirigimos a C:\Usuarios (C:\Users)

Dentro de la carpeta Usuarios, encontraremos el nombre del usuario con el cual te has identificado en Windows.

![Carpeta de usuarios](https://todoconta.s3-us-west-1.amazonaws.com/soporte/usuarios-windows.png)

Dentro de la carpeta de usuarios buscamos la siguiente ubicación \AppData\Local\Apps\2.0.

La carpeta AppData se encuentra en modo oculto así que para ello tendrás que habilitar la opción de Mostrar archivos ocultos dentro de las opciones de carpeta o bien puedes copiar la siguiente ubicación en la barra de navegación del Explorador de archivos de Windows.

C:\Users\TU USUARIO\AppData\Local\Apps\2.0

![Caperta AppData](https://todoconta.s3-us-west-1.amazonaws.com/soporte/caperta-20.png)

Tenemos que eliminar el contenido completo de esta carpeta y reinstalamos la aplicación.

👉 [Comprar timbres](https://todoconta.com/cfdifacturas)
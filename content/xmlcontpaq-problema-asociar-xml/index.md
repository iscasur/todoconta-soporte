---
title: La aplicación no asocia los XML a la póliza en CONTPAQi® Contabilidad
date: 2016-05-14
author: iscasur
modifiedDate: null
description: "Solución al problema para convertir XML a PDF de versiones 3.2 y 3.3"
---
El detalle del porque la aplicación [XML a Contpaqi](https://todoconta.com/xmlcontpaq) no se asocian los archivos XML el 99% de los casos es por lo siguiente:

Las herramientas de CONTPAQi® Contabilidad actualmente están algo limitadas en cuestión de cargar información externa (archivo txt), lo que muy probablemente sucedió es que algún archivo XML que se considero para realizar la póliza **no estaba cargado en el ADD**.

> Por ejemplo si generaste 1, 5 o 10 pólizas en un mismo archivo de texto y si dentro de estas pólizas existe 1 archivo XML que no esta en el ADD cargado no se realiza ninguna asociación de ningún archivo XML que contenga todo el lote del archivo de texto así sean números de pólizas diferentes ya que CONTPAQi® Contabilidad considera los datos del archivo de texto como un todo.

Es importante asegurarte que antes de cargar la póliza a CONTPAQi® Contabilidad los archivos XML considerados para la misma todos y cada uno de los archivos XML estén debidamente cargados en el ADD, una vez realizando esto al subir la póliza realizará las asociaciones a los documentos XML correspondientes.

También puedes realizar esta otra alternativa:

Desde el menú de CONTPAQi® Contabilidad habiendo seleccionado la empresa ir al menú:

> Empresas > Utilerías > Reconstruir asociación en el ADD.

Lo anterior sirve para reconstruir las asociaciones realizadas de forma errónea que fueron causadas por la interface de CONTPAQi® Contabilidad con el ADD.
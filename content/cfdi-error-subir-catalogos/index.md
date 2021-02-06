---
title: Error al subir los catálogos con el layout de Excel
date: 2016-05-14
author: iscasur
modifiedDate: null
description: "Solución al error al subir los catálogos con el layout de Excel"
---
Este problema se origina porque se está abriendo un archivo de Excel en formato *.xlsx (versión nueva), y nuestro programa solo puede leer archivos *.xls.

La solución es **convertir el formato de tu archivo *.xlsx** y guardarla como libro Excel 97-2003 que es el formato *.xls.

Para ello una vez abrierlo el archivo con la aplicación Excel, diríjase al menú Archivo – Guardar cómo y en tipo seleccionar "Libro de Excel 97-2003".
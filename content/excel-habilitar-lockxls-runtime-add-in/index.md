---
title: Solución al error – LockXLS Runtime Add-in se encuentra desabilitado
date: 2016-09-05
author: iscasur
modifiedDate: null
description: "Si vas a cambiar de equipo, puedes trasladar tu licencia sin costo"
---

### Problema

Al momento de abrir la aplicación* me aparece el siguiente mensaje:

![LockXLS Runtime Add-in](https://todoconta.s3-us-west-1.amazonaws.com/soporte/lockxls-runtime-add-in.png)

Por la descripción del error es muy probable que *el Firewall o antivirus de tu equipo esté bloqueando el complemento (LockXLS)* que es necesario para la ejecución del software.

### Solución

Para que funcione correctamente la aplicación se deberá asegurar de agregar a lista de exclusión del antivirus o firewall las siguientes rutas para que no los inhabilite de nuevo.

- C:\XLSAPPS\
- C:\Program Files\Control XML-CFDI\

Una vez realizado lo anterior sigue los pasos del siguiente vídeo para **habilitar el complemento LockXLS** y el software volverá a funcionar de nuevo como la venía estado haciendo.

<iframe src="https://www.youtube.com/embed/PwipmjJW1PE" width="640" height="360" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Si con las indicaciones anteriores se continúa con el error, otra causa también pude ser que la aplicación se tenga que ejecutar en el equipo con permiso de administrador.

Desde la siguiente ruta posicionándose sobre el icono de la aplicación Control XML-CFDI.exe  (C:\XLSApps\Control XML-CFDI\) haga click derecho con el mouse y selecciona la opción «Ejecutar como Administrador«.

## Microsoft Excel a 64 Bits

El Software por default se instala en Excel para 32 bits, que es el estándar de la mayoría de office, si se tiene instalado Excel a 64 bits se deberá descargar e instalar este componente: http://bit.ly/2rXLKhy.

Al ejecutar el instalador es necesario tener todas las sesiones de Excel cerradas, una vez instalado abre nuevamente la aplicación* y deberá funcionar sin problemas.
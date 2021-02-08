---
title: XML a CTQPi v6 no inicia correctamente
date: 2021-02-08
author: iscasur
modifiedDate: null
description: "Solución al problema 'The feature you are trying to use is on network resource that is unavaible'"
---
### Problema
Al abrir le aplicación [XML a CTQPi](https://todoconta.com/xmlcontpaq) me muestra el siguiente mensaje:

![The feature you are trying to use is on network resource that is unavaible](https://todoconta.s3-us-west-1.amazonaws.com/soporte/001-xmlactpqi-feature-unavailable.png)

### Solución
Por la descripción del error parece que el antivirus del equipo esta enviando a cuarentena el ejecutable de la aplicación, se deberá **reinstalar la aplicación**.

Para que te permita instalar la herramienta te sugiero **deshabilitar temporalmente el antivirus** durante la instalación y una vez se haya reinstalado la herramienta asegúrate de **agregar a lista de exclusión** de tu antivirus o firewall las siguientes rutas para que el antivirus no bloquee la ejecución de la aplicación, reiniciar tu equipo para que se apliquen todos los cambios en el equipo.

- C:\XLSApps\
- C:\XLSApps\XMLaCTPQi\XML a CTPQi.EXE
- C:\Program Files\LockXLS\LockXLS64Runtime.dll
- C:\Program Files (x86)\LockXLS\LockXLSRuntime.dll

Para reinstalar y activar la aplicación se deberá realizar lo siguiente:

1. Reinicia tu equipo para que se liberen la sesiones abiertas en la memoria caché que pudieran existir de la aplicación **XML a CTPQi v6**
2. En la carpeta **C:\XLSApps\XMLaCTPQi\\** eliminar el archivo (si es que existe) llamado **XML a CTPQi.xlsm (archivo de Excel)**
3. Desde la siguiente liga descargar el instalador de la aplicación XML a CTPQi v6: https://bit.ly/3kw40pu

Para instalar la nueva versión del software XML a CTPQi v6 se deberá desinstalar en primera instancia la versión anterior.

Con el nuevo instalador de la versión al iniciarse detectará que existe una versión anterior, elige la opción **Remover** para que se desinstale totalmente la versión anterior instalada y una vez finalizado el proceso ejecuta nuevamente el instalador para que se instale la nueva versión.

Se deberá ingresar en caso de solicitarlo la licencia que se te proporcionó cuando adquiriste el software, el código de equipo no cambia es fijo para esta versión.

La aplicación se deberá abrir desde el acceso directo que se creó en el escritorio.
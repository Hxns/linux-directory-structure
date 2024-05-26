# Directorios del Sistema de Archivos en Linux

Este documento proporciona una descripción de los principales directorios del sistema de archivos en Linux y su propósito.

## Directorios del Sistema y Descripciones

| Ruta   | Descripción                                                                 |
|--------|-----------------------------------------------------------------------------|
| `/`    | El directorio de nivel superior es el sistema de archivos raíz y contiene todos los archivos necesarios para arrancar el sistema operativo antes de montar otros sistemas de archivos, así como los archivos necesarios para arrancar los otros sistemas de archivos. Después del arranque, todos los demás sistemas de archivos se montan en puntos de montaje estándar como subdirectorios del raíz. |
| `/bin` | Contiene los binarios de comando esenciales.                                |
| `/boot`| Consiste en el cargador de arranque estático, el ejecutable del kernel y los archivos necesarios para arrancar el sistema operativo Linux. |
| `/dev` | Contiene archivos de dispositivo para facilitar el acceso a cada dispositivo de hardware conectado al sistema. |
| `/etc` | Archivos de configuración del sistema local. Los archivos de configuración para las aplicaciones instaladas también pueden guardarse aquí. |
| `/home`| Cada usuario en el sistema tiene un subdirectorio aquí para almacenamiento. |
| `/lib` | Archivos de bibliotecas compartidas que son necesarios para el arranque del sistema. |
| `/media`| Los dispositivos de medios extraíbles como unidades USB se montan aquí.     |
| `/mnt` | Punto de montaje temporal para sistemas de archivos regulares.              |
| `/opt` | Los archivos opcionales, como herramientas de terceros, pueden guardarse aquí. |
| `/root`| El directorio de inicio para el usuario root.                               |
| `/sbin`| Este directorio contiene ejecutables utilizados para la administración del sistema (archivos binarios del sistema). |
| `/tmp` | El sistema operativo y muchos programas utilizan este directorio para almacenar archivos temporales. Este directorio generalmente se borra al arrancar el sistema y puede eliminarse en otros momentos sin previo aviso. |
| `/usr` | Contiene ejecutables, bibliotecas, archivos de manual, etc.                 |
| `/var` | Este directorio contiene archivos de datos variables, como archivos de registro, bandejas de entrada de correo electrónico, archivos relacionados con aplicaciones web, archivos cron, y más. |

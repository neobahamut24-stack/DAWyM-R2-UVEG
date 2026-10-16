# Gestor de tareas — Reto 2 UVEG

## Descripción

Aplicación web desarrollada como proyecto académico para el módulo **Despliegue de aplicaciones web y móviles v2**, correspondiente al **Reto 2: Prepara y lanza tu aplicación web**.

Permite agregar tareas, marcarlas como completadas, eliminarlas y limpiar las tareas completadas.

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- Apache mediante XAMPP
- Git y GitHub
- Terser para minificar JavaScript
- clean-css-cli para minificar CSS

## Estructura del proyecto

- `index.html`: página principal.
- `css/styles.css`: hoja de estilos original.
- `css/styles.min.css`: hoja de estilos minificada.
- `js/app.js`: lógica JavaScript original.
- `js/app.min.js`: JavaScript minificado.
- `img/universidad-uveg.jpg`: imagen institucional.
- `Jaramillo_Vicente_R2_U2.zip`: paquete comprimido de la aplicación, generado por separado.

## Preparación y empaquetado

Los archivos se organizaron en carpetas para facilitar su mantenimiento. Se generaron versiones minificadas de CSS y JavaScript mediante **clean-css-cli** y **Terser**. La imagen institucional se revisó y se incluyó en la carpeta `img`. Finalmente, se creó un paquete ZIP con los archivos necesarios para ejecutar la aplicación, sin incluir dependencias de desarrollo.

## Control de versiones

El proyecto se administra mediante Git y se publica en GitHub.

Repositorio: [DAWyM-R2-UVEG](https://github.com/neobahamut24-stack/DAWyM-R2-UVEG)

## Configuración y despliegue con Apache

El servidor web utilizado es Apache, instalado mediante XAMPP en Windows.

- **Puerto HTTP:** 80.
- **Directorio de la aplicación:** `C:/xampp/htdocs/gestor-tereas-UVEG`.
- **Archivo de configuración de Virtual Hosts:** `C:/xampp/apache/conf/extra/httpd-vhosts.conf`.
- **Nombre local configurado:** `gestor-tereas-uveg.local`.
- **Resolución local:** entrada en el archivo `C:/Windows/System32/drivers/etc/hosts` que asocia el nombre con `127.0.0.1`.

La configuración del Virtual Host permite acceder a la aplicación mediante:

- [http://gestor-tereas-uveg.local/](http://gestor-tereas-uveg.local/)
- [http://localhost/gestor-tereas-UVEG/](http://localhost/gestor-tereas-UVEG/)

Estas direcciones son de uso local; no representan una publicación pública en Internet.

## Verificación

Se comprobó la sintaxis de la configuración de Apache con `httpd.exe -t`, cuyo resultado fue `Syntax OK`. También se verificó el registro del Virtual Host mediante `httpd.exe -S` y se abrió la aplicación en el navegador.

## Autor

Proyecto académico UVEG.

<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Tube para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/tube.svg)](https://dash.yunohost.org/appci/app/tube) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/tube.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/tube.maintain.svg)

[![Instalar Tube con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tube)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarTube rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Tube is a Youtube-like (without censorship and features you don't need!) Video Sharing App written in Go which also supports automatic transcoding to MP4 H.265 AAC, multiple collections and RSS feed.

### Features

- Easy to add videos (just move a file into the folder)
- Easy to upload videos (just use the builtin uploader and automatic transcoder!)
- Builtin ffmpeg-based Transcoder that automatically converts your uploaded content to MP4 H.264 / AAC
- Builtin automatic thumbnail generator
- No database (video info pulled from file metadata)
- No JavaScript (the player UI is entirely HTML, except for the uploader which degrades!)
- Easy to customize CSS and HTML template
- Automatically generates RSS feed (at /feed.xml)
- Clean, simple, familiar UI


**Versión actual:** 1.2.0~ynh3

**Demo:** <https://tube.mills.io>

## Capturas

![Captura de Tube](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Sitio web oficial: <https://tube.mills.io>
- Repositorio del código fuente oficial de la aplicación : <https://git.mills.io/prologic/tube>
- Catálogo YunoHost: <https://apps.yunohost.org/app/tube>
- Reportar un error: <https://github.com/YunoHost-Apps/tube_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/tube_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
o
sudo yunohost app upgrade tube -u https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>

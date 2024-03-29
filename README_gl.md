<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Tube para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/tube.svg)](https://dash.yunohost.org/appci/app/tube) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/tube.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/tube.maintain.svg)

[![Instalar Tube con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tube)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Tube de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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


**Versión proporcionada:** 1.2.0~ynh3

**Demo:** <https://tube.mills.io>

## Capturas de pantalla

![Captura de pantalla de Tube](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Web oficial da app: <https://tube.mills.io>
- Repositorio de orixe do código: <https://git.mills.io/prologic/tube>
- Tenda YunoHost: <https://apps.yunohost.org/app/tube>
- Informar dun problema: <https://github.com/YunoHost-Apps/tube_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/tube_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
ou
sudo yunohost app upgrade tube -u https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>

<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Tube per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/tube.svg)](https://dash.yunohost.org/appci/app/tube) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/tube.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/tube.maintain.svg)

[![Installa Tube con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tube)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Tube su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

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


**Versione pubblicata:** 1.2.0~ynh3

**Prova:** <https://tube.mills.io>

## Screenshot

![Screenshot di Tube](./doc/screenshots/screenshot.png)

## Documentazione e risorse

- Sito web ufficiale dell’app: <https://tube.mills.io>
- Repository upstream del codice dell’app: <https://git.mills.io/prologic/tube>
- Store di YunoHost: <https://apps.yunohost.org/app/tube>
- Segnala un problema: <https://github.com/YunoHost-Apps/tube_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/tube_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
o
sudo yunohost app upgrade tube -u https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>

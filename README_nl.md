<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Tube voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/tube)](https://ci-apps.yunohost.org/ci/apps/tube/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/tube)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/tube)

[![Tube met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tube)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Tube snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

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


**Geleverde versie:** 1.2.0~ynh3

## Schermafdrukken

![Schermafdrukken van Tube](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Upstream app codedepot: <https://git.mills.io/prologic/tube>
- YunoHost-store: <https://apps.yunohost.org/app/tube>
- Meld een bug: <https://github.com/YunoHost-Apps/tube_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/tube_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
of
sudo yunohost app upgrade tube -u https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>

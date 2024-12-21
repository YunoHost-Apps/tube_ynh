<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Tube dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/tube)](https://ci-apps.yunohost.org/ci/apps/tube/)
![Status działania](https://apps.yunohost.org/badge/state/tube)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/tube)

[![Zainstaluj Tube z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tube)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Tube na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

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


**Dostarczona wersja:** 1.2.0~ynh3

## Zrzuty ekranu

![Zrzut ekranu z Tube](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Repozytorium z kodem źródłowym: <https://git.mills.io/prologic/tube>
- Sklep YunoHost: <https://apps.yunohost.org/app/tube>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/tube_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/tube_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
lub
sudo yunohost app upgrade tube -u https://github.com/YunoHost-Apps/tube_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>

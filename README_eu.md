<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Epicyon YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/epicyon.svg)](https://dash.yunohost.org/appci/app/epicyon) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/epicyon.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/epicyon.maintain.svg)

[![Instalatu Epicyon YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=epicyon)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Epicyon YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

ActivityPub server implementing S2S and C2S protocols, suitable for single board computers. Includes features such as moderation tools, post expiry, content warnings, and image descriptions


**Paketatutako bertsioa:** 2023.03.17~ynh2

## Pantaila-argazkiak

![Epicyon(r)en pantaila-argazkia](./doc/screenshots/screenshot_starlight.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://epicyon.net>
- Jatorrizko aplikazioaren kode-gordailua: <https://gitlab.com/bashrc2/epicyon/>
- YunoHost Denda: <https://apps.yunohost.org/app/epicyon>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/epicyon_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/epicyon_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/epicyon_ynh/tree/testing --debug
edo
sudo yunohost app upgrade epicyon -u https://github.com/YunoHost-Apps/epicyon_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>

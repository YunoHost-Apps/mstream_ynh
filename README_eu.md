<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# mStream YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/mstream)](https://ci-apps.yunohost.org/ci/apps/mstream/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/mstream)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/mstream)

[![Instalatu mStream YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mstream)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek mStream YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

mStream is a personal music streaming server. You can use mStream to stream your music from your home computer to any device, anywhere.

### Features

- Light on memory and CPU
- Tested on multi-terabyte libraries
- Runs on ARM boards like the Raspberry Pi


**Paketatutako bertsioa:** 5.13.1~ynh1

**Demoa:** <https://demo.mstream.io/>

## Pantaila-argazkiak

![mStream(r)en pantaila-argazkia](./doc/screenshots/mstreamv5.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://mstream.io/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/IrosTheBeggar/mStream>
- YunoHost Denda: <https://apps.yunohost.org/app/mstream>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/mstream_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/mstream_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mstream_ynh/tree/testing --debug
edo
sudo yunohost app upgrade mstream -u https://github.com/YunoHost-Apps/mstream_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>

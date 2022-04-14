# mStream pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/mstream.svg)](https://dash.yunohost.org/appci/app/mstream) ![](https://ci-apps.yunohost.org/ci/badges/mstream.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mstream.maintain.svg)  
[![Installer mStream avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mstream)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer mStream rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Some long and extensive description of what the app is and does, lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

### Features

    Cross Platform. Works on Windows, OSX, Linux, & FreeBSD
    Light on memory and CPU
    Tested on multi-terabyte libraries
    Runs on ARM boards like the Raspberry Pi


**Version incluse :** 5.11.4~ynh1

**Démo :** https://demo.mstream.io/?

## Captures d'écran

![](./doc/screenshots/mstreamv5.png)

## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentations et ressources

* Site officiel de l'app : https://mstream.io/
* Documentation officielle utilisateur : https://yunohost.org/apps
* Documentation officielle de l'admin : https://yunohost.org/packaging_apps
* Dépôt de code officiel de l'app : https://github.com/IrosTheBeggar/mStream
* Documentation YunoHost pour cette app : https://yunohost.org/app_mstream
* Signaler un bug : https://github.com/YunoHost-Apps/mstream_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/mstream_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mstream_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mstream -u https://github.com/YunoHost-Apps/mstream_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps
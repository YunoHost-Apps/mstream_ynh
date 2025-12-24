<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# mStream pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/mstream)](https://ci-apps.yunohost.org/ci/apps/mstream/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/mstream)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/mstream)

[![Installer mStream avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=mstream)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer mStream rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

mStream est un serveur de streaming musical personnel. Vous pouvez utiliser mStream pour diffuser votre musique depuis votre ordinateur personnel vers n'importe quel appareil, n'importe où.

### Caractéristiques

- Économe en mémoire et en CPU
- Testé sur des bibliothèques multi-téraoctets
- Fonctionne sur des cartes ARM comme le Raspberry Pi

**Version incluse :** 5.13.1~ynh1

**Démo :** <https://demo.mstream.io/>

## Captures d’écran

![Capture d’écran de mStream](./doc/screenshots/mstreamv5.png)

## Documentations et ressources

- Site officiel de l’app : <https://mstream.io/>
- Dépôt de code officiel de l’app : <https://github.com/IrosTheBeggar/mStream>
- YunoHost Store : <https://apps.yunohost.org/app/mstream>
- Signaler un bug : <https://github.com/YunoHost-Apps/mstream_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/mstream_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/mstream_ynh/tree/testing --debug
ou
sudo yunohost app upgrade mstream -u https://github.com/YunoHost-Apps/mstream_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>

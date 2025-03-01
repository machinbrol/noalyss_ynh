# Noalyss pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/noalyss.svg)](https://dash.yunohost.org/appci/app/noalyss) ![](https://ci-apps.yunohost.org/ci/badges/noalyss.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/noalyss.maintain.svg)  
[![Installer Noalyss avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=noalyss)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Noalyss rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Noalyss est un serveur de comptabilité destiné à être hébergé sur Internet afin de contenir la comptabilité d’un nombre illimité de sociétés et d’utilisateurs ne se connaissant pas. Chaque société a ses propres dossiers comptables , ses propres utilisateurs, et ne peut pas interférer avec la comptabilité des autres, à moins d’y être expressément autorisé.

**Version incluse :** 9.0.1.1~ynh1

**Démo :** http://demo.noalyss.eu/index.php

## Captures d'écran

![](./doc/screenshots/Sélection_099_0.png)

## Avertissements / informations importantes

### Configuration

À la fin de l'installation de l'application il faut se rendre sur `https://domaine/noalyss/install.php` pour terminer la procédure.

## Documentations et ressources

* Site officiel de l'app : http://noalyss.eu
* Documentation officielle de l'admin : https://wiki.noalyss.eu/doku.php
* Documentation YunoHost pour cette app : https://yunohost.org/app_noalyss
* Signaler un bug : https://github.com/YunoHost-Apps/noalyss_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/noalyss_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/noalyss_ynh/tree/testing --debug
ou
sudo yunohost app upgrade noalyss -u https://github.com/YunoHost-Apps/noalyss_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps
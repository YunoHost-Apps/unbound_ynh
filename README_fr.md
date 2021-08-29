# Unbound pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/unbound.svg)](https://dash.yunohost.org/appci/app/unbound) ![](https://ci-apps.yunohost.org/ci/badges/unbound.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/unbound.maintain.svg)  
[![Installer Unbound avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=unbound)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Unbound rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Serveur DNS de mise en cache uniquement récursif

**Version incluse :** 1.9.0~ynh1

**Démo :** https://demo.example.com

## Documentations et ressources

* Site officiel de l'app : https://nlnetlabs.nl/projects/unbound/about/
* Documentation officielle utilisateur : https://yunohost.org/apps
* Documentation officielle de l'admin : https://nlnetlabs.nl/documentation/unbound/
* Dépôt de code officiel de l'app : https://some.forge.com/example/example
* Documentation YunoHost pour cette app : https://yunohost.org/app_unbound
* Signaler un bug : https://github.com/YunoHost-Apps/unbound_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/unbound_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/unbound_ynh/tree/testing --debug
ou
sudo yunohost app upgrade unbound -u https://github.com/YunoHost-Apps/unbound_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps
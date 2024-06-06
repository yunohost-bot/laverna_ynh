<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Laverna pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/laverna.svg)](https://dash.yunohost.org/appci/app/laverna) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/laverna.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/laverna.maintain.svg)

[![Installer Laverna avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=laverna)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Laverna rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Laverna est un système anonyme, crypté et sans inscription requise, il est accessible via un navigateur web (sans installation de logiciel).
Les données sont privées, car stockées par défaut sur votre machine (InnoDB et localstorage), c’est un réglage dans les paramètres qui vous permettra de les synchroniser via le cloud sur vos différents périphériques.


**Version incluse :** 0.7.51~ynh6

**Démo :** <https://laverna.cc/app/>

## Captures d’écran

![Capture d’écran de Laverna](./doc/screenshots/laverna.png)

## :red_circle: Anti-fonctionnalités

- **Application non maintenue **: Ce logiciel n'est plus maintenu. Attendez-vous à ce qu'il ne fonctionne plus avec le temps, et que l'on découvre des failles de sécurité qui ne seront pas corrigées, etc.
- **Package non maintenu **: Ce package YunoHost n'est pas activement maintenu et a besoin d'être adopté. Cela veut dire que la maintenance minimale est réalisée par des bénévoles qui n'utilisent pas l'application, il faut donc s'attendre à ce que l'app perde en fiabilité avec le temps. Vous pouvez [apprendre comment packager](https://yunohost.org/packaging_apps_intro) si vous voulez l'adopter.

## Documentations et ressources

- Site officiel de l’app : <https://laverna.cc/index.html>
- Documentation officielle de l’admin : <https://github.com/Laverna/laverna/wiki>
- Dépôt de code officiel de l’app : <https://github.com/Laverna/laverna>
- YunoHost Store : <https://apps.yunohost.org/app/laverna>
- Signaler un bug : <https://github.com/YunoHost-Apps/laverna_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/laverna_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/laverna_ynh/tree/testing --debug
ou
sudo yunohost app upgrade laverna -u https://github.com/YunoHost-Apps/laverna_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>

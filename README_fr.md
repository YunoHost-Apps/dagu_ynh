<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Dagu pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/dagu.svg)](https://ci-apps.yunohost.org/ci/apps/dagu/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/dagu.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/dagu.maintain.svg)

[![Installer Dagu avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dagu)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Dagu rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Dagu est une alternative puissante à Cron qui est fournie avec une interface utilisateur Web. Il vous permet de définir des dépendances entre les commandes sous forme de graphe acyclique dirigé (DAG) dans un format YAML déclaratif. Dagu simplifie la gestion et l'exécution de flux de travail complexes. Il prend en charge nativement l'exécution de conteneurs Docker, la création de requêtes HTTP et l'exécution de commandes via SSH.


**Version incluse :** 1.14.5~ynh1

## Captures d’écran

![Capture d’écran de Dagu](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Documentation officielle de l’admin : <https://dagu.readthedocs.io/en/latest/>
- Dépôt de code officiel de l’app : <https://github.com/dagu-org/dagu>
- YunoHost Store : <https://apps.yunohost.org/app/dagu>
- Signaler un bug : <https://github.com/YunoHost-Apps/dagu_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/dagu_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dagu -u https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>

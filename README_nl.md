<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Dagu voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/dagu)](https://ci-apps.yunohost.org/ci/apps/dagu/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/dagu)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/dagu)

[![Dagu met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dagu)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Dagu snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Dagu is a powerful Cron alternative that comes with a Web UI. It allows you to define dependencies between commands as a Directed Acyclic Graph (DAG) in a declarative YAML format. Dagu simplifies the management and execution of complex workflows. It natively supports running Docker containers, making HTTP requests, and executing commands over SSH.


**Geleverde versie:** 1.16.6~ynh1

## Schermafdrukken

![Schermafdrukken van Dagu](./doc/screenshots/screenshot.png)

## Documentatie en bronnen

- Officiele beheerdersdocumentatie: <https://dagu.readthedocs.io/en/latest/>
- Upstream app codedepot: <https://github.com/dagu-org/dagu>
- YunoHost-store: <https://apps.yunohost.org/app/dagu>
- Meld een bug: <https://github.com/YunoHost-Apps/dagu_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/dagu_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
of
sudo yunohost app upgrade dagu -u https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>

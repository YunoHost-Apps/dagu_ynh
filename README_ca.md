<!--
N.B.: Aquest README ha estat generat automàticament per <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NO s'ha de modificar manualment.
-->

# Dagu per YunoHost

[![Nivell d'integració](https://apps.yunohost.org/badge/integration/dagu)](https://ci-apps.yunohost.org/ci/apps/dagu/)
![Estat de funcionament](https://apps.yunohost.org/badge/state/dagu)
![Estat de manteniment](https://apps.yunohost.org/badge/maintained/dagu)

[![Instal·la Dagu amb YunoHosth](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dagu)

*[Llegeix aquest README en altres idiomes.](./ALL_README.md)*

> *Aquest paquet et permet instal·lar Dagu de forma ràpida i senzilla en un servidor YunoHost.*  
> *Si no tens YunoHost, consulta [la guia](https://yunohost.org/install) per saber com instal·lar-lo.*

## Visió general

Dagu is a powerful Cron alternative that comes with a Web UI. It allows you to define dependencies between commands as a Directed Acyclic Graph (DAG) in a declarative YAML format. Dagu simplifies the management and execution of complex workflows. It natively supports running Docker containers, making HTTP requests, and executing commands over SSH.


**Versió inclosa:** 1.16.7~ynh1

## Captures de pantalla

![Captures de pantalla de Dagu](./doc/screenshots/screenshot.png)

## Documentació i recursos

- Documentació oficial per l'administrador: <https://dagu.readthedocs.io/en/latest/>
- Repositori oficial del codi de l'aplicació: <https://github.com/dagu-org/dagu>
- Botiga YunoHost: <https://apps.yunohost.org/app/dagu>
- Reportar un error: <https://github.com/YunoHost-Apps/dagu_ynh/issues>

## Informació per a desenvolupadors

Envieu les pull request a la [branca `testing`](https://github.com/YunoHost-Apps/dagu_ynh/tree/testing).

Per provar la branca `testing`, procedir com descrit a continuació:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
o
sudo yunohost app upgrade dagu -u https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
```

**Més informació sobre l'empaquetatge d'aplicacions:** <https://yunohost.org/packaging_apps>

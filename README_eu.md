<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Dagu YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/dagu)](https://ci-apps.yunohost.org/ci/apps/dagu/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/dagu)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/dagu)

[![Instalatu Dagu YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dagu)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Dagu YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Dagu is a powerful Cron alternative that comes with a Web UI. It allows you to define dependencies between commands as a Directed Acyclic Graph (DAG) in a declarative YAML format. Dagu simplifies the management and execution of complex workflows. It natively supports running Docker containers, making HTTP requests, and executing commands over SSH.


**Paketatutako bertsioa:** 1.16.5~ynh1

## Pantaila-argazkiak

![Dagu(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://dagu.readthedocs.io/en/latest/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/dagu-org/dagu>
- YunoHost Denda: <https://apps.yunohost.org/app/dagu>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/dagu_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/dagu_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
edo
sudo yunohost app upgrade dagu -u https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>

<!--
N.B.: Diese README wurde automatisch von <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> generiert.
Sie darf NICHT von Hand bearbeitet werden.
-->

# Dagu für YunoHost

[![Integrations-Level](https://apps.yunohost.org/badge/integration/dagu)](https://ci-apps.yunohost.org/ci/apps/dagu/)
![Funktionsstatus](https://apps.yunohost.org/badge/state/dagu)
![Wartungsstatus](https://apps.yunohost.org/badge/maintained/dagu)

[![Dagu mit YunoHost installieren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dagu)

*[Dieses README in anderen Sprachen lesen.](./ALL_README.md)*

> *Mit diesem Paket können Sie Dagu schnell und einfach auf einem YunoHost-Server installieren.*  
> *Wenn Sie YunoHost nicht haben, lesen Sie bitte [die Anleitung](https://yunohost.org/install), um zu erfahren, wie Sie es installieren.*

## Übersicht

Dagu is a powerful Cron alternative that comes with a Web UI. It allows you to define dependencies between commands as a Directed Acyclic Graph (DAG) in a declarative YAML format. Dagu simplifies the management and execution of complex workflows. It natively supports running Docker containers, making HTTP requests, and executing commands over SSH.


**Ausgelieferte Version:** 1.16.7~ynh1

## Bildschirmfotos

![Bildschirmfotos von Dagu](./doc/screenshots/screenshot.png)

## Dokumentation und Ressourcen

- Offizielle Verwaltungsdokumentation: <https://dagu.readthedocs.io/en/latest/>
- Upstream App Repository: <https://github.com/dagu-org/dagu>
- YunoHost-Shop: <https://apps.yunohost.org/app/dagu>
- Einen Fehler melden: <https://github.com/YunoHost-Apps/dagu_ynh/issues>

## Entwicklerinformationen

Bitte senden Sie Ihren Pull-Request an den [`testing` branch](https://github.com/YunoHost-Apps/dagu_ynh/tree/testing).

Um den `testing` Branch auszuprobieren, gehen Sie bitte wie folgt vor:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
oder
sudo yunohost app upgrade dagu -u https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
```

**Weitere Informationen zur App-Paketierung:** <https://yunohost.org/packaging_apps>

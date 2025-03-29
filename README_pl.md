<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Dagu dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/dagu)](https://ci-apps.yunohost.org/ci/apps/dagu/)
![Status działania](https://apps.yunohost.org/badge/state/dagu)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/dagu)

[![Zainstaluj Dagu z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dagu)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Dagu na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Dagu is a powerful Cron alternative that comes with a Web UI. It allows you to define dependencies between commands as a Directed Acyclic Graph (DAG) in a declarative YAML format. Dagu simplifies the management and execution of complex workflows. It natively supports running Docker containers, making HTTP requests, and executing commands over SSH.


**Dostarczona wersja:** 1.16.7~ynh1

## Zrzuty ekranu

![Zrzut ekranu z Dagu](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Oficjalna dokumentacja dla administratora: <https://dagu.readthedocs.io/en/latest/>
- Repozytorium z kodem źródłowym: <https://github.com/dagu-org/dagu>
- Sklep YunoHost: <https://apps.yunohost.org/app/dagu>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/dagu_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/dagu_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
lub
sudo yunohost app upgrade dagu -u https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>

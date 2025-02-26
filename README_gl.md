<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Dagu para YunoHost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/dagu)](https://ci-apps.yunohost.org/ci/apps/dagu/)
![Estado de funcionamento](https://apps.yunohost.org/badge/state/dagu)
![Estado de mantemento](https://apps.yunohost.org/badge/maintained/dagu)

[![Instalar Dagu con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dagu)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Dagu de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Dagu is a powerful Cron alternative that comes with a Web UI. It allows you to define dependencies between commands as a Directed Acyclic Graph (DAG) in a declarative YAML format. Dagu simplifies the management and execution of complex workflows. It natively supports running Docker containers, making HTTP requests, and executing commands over SSH.


**Versión proporcionada:** 1.16.4~ynh1

## Capturas de pantalla

![Captura de pantalla de Dagu](./doc/screenshots/screenshot.png)

## Documentación e recursos

- Documentación oficial para admin: <https://dagu.readthedocs.io/en/latest/>
- Repositorio de orixe do código: <https://github.com/dagu-org/dagu>
- Tenda YunoHost: <https://apps.yunohost.org/app/dagu>
- Informar dun problema: <https://github.com/YunoHost-Apps/dagu_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/dagu_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
ou
sudo yunohost app upgrade dagu -u https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>

<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Dagu para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/dagu.svg)](https://ci-apps.yunohost.org/ci/apps/dagu/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/dagu.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/dagu.maintain.svg)

[![Instalar Dagu con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dagu)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarDagu rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Dagu is a powerful Cron alternative that comes with a Web UI. It allows you to define dependencies between commands as a Directed Acyclic Graph (DAG) in a declarative YAML format. Dagu simplifies the management and execution of complex workflows. It natively supports running Docker containers, making HTTP requests, and executing commands over SSH.


**Versión actual:** 1.14.5~ynh2

## Capturas

![Captura de Dagu](./doc/screenshots/screenshot.png)

## Documentaciones y recursos

- Documentación administrador oficial: <https://dagu.readthedocs.io/en/latest/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/dagu-org/dagu>
- Catálogo YunoHost: <https://apps.yunohost.org/app/dagu>
- Reportar un error: <https://github.com/YunoHost-Apps/dagu_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/dagu_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
o
sudo yunohost app upgrade dagu -u https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>

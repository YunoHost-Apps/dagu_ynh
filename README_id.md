<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Dagu untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/dagu)](https://ci-apps.yunohost.org/ci/apps/dagu/)
![Status kerja](https://apps.yunohost.org/badge/state/dagu)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/dagu)

[![Pasang Dagu dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dagu)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Dagu secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Dagu is a powerful Cron alternative that comes with a Web UI. It allows you to define dependencies between commands as a Directed Acyclic Graph (DAG) in a declarative YAML format. Dagu simplifies the management and execution of complex workflows. It natively supports running Docker containers, making HTTP requests, and executing commands over SSH.


**Versi terkirim:** 1.16.3~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Dagu](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Dokumentasi admin resmi: <https://dagu.readthedocs.io/en/latest/>
- Depot kode aplikasi hulu: <https://github.com/dagu-org/dagu>
- Gudang YunoHost: <https://apps.yunohost.org/app/dagu>
- Laporkan bug: <https://github.com/YunoHost-Apps/dagu_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/dagu_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
atau
sudo yunohost app upgrade dagu -u https://github.com/YunoHost-Apps/dagu_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
